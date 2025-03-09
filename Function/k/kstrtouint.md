# Function: <code>kstrtouint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047248,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:218",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:max_recycle_threshold_store",
        "kernel/params.c:param_set_uint",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/hung_task.c:hung_task_panic_setup",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "fs/fuse/inode.c:fuse_match_uint",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/host/ehci-hcd.c:store_uframe_periodic_max",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_core.c:sustainable_power_store",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/dm.c:dm_attr_rq_based_seq_io_merge_deadline_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:set_tx_maxrate",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047248,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583340800,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:218",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:max_recycle_threshold_store",
        "kernel/params.c:param_set_uint",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/hung_task.c:hung_task_panic_setup",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "fs/fuse/inode.c:fuse_match_uint",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/host/ehci-hcd.c:store_uframe_periodic_max",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_core.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:set_tx_maxrate",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340800,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583466176,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:214",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:max_recycle_threshold_store",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/hung_task.c:hung_task_panic_setup",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "fs/fuse/inode.c:fuse_match_uint",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/host/ehci-hcd.c:store_uframe_periodic_max",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:set_tx_maxrate",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583466176,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583488448,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:216",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "fs/fuse/inode.c:fuse_match_uint",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/host/ehci-hcd.c:store_uframe_periodic_max",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:set_tx_maxrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488448,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583669488,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "fs/fuse/inode.c:fuse_match_uint",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/host/ehci-hcd.c:store_uframe_periodic_max",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669488,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583887264,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_events_hist.c:create_synth_event",
        "kernel/trace/trace_kprobe.c:create_trace_kprobe",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fuse/inode.c:fuse_match_uint",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887264,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971504,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fuse/inode.c:fuse_match_uint",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/nvdimm/dimm_devs.c:security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971504,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584152720,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fuse/inode.c:fuse_match_uint",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/nvdimm/dimm_devs.c:__security_store",
        "drivers/nvdimm/dimm_devs.c:__security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152720,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584275344,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275344,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584685547,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtouint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_early_khz_setup",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/proc/root.c:proc_parse_param",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:parse_policy_line",
        "security/safesetid/securityfs.c:parse_policy_line",
        "security/device_cgroup.c:devcgroup_update_access",
        "security/device_cgroup.c:devcgroup_update_access",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/dynamic_debug.c:ddebug_parse_query",
        "lib/dynamic_debug.c:ddebug_parse_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/watchdog/watchdog_dev.c:nowayout_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/cpuidle/sysfs.c:store_state_disable",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_limit_min",
        "net/core/net-sysfs.c:bql_set_limit_max",
        "net/core/net-sysfs.c:bql_set_limit",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684736,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584803115,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:214",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtouint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_early_khz_setup",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/reboot.c:cpu_store",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/ksm.c:run_store",
        "mm/ksm.c:pages_to_scan_store",
        "mm/ksm.c:sleep_millisecs_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/memtest.c:parse_memtest",
        "mm/khugepaged.c:pages_to_scan_store",
        "mm/khugepaged.c:alloc_sleep_millisecs_store",
        "mm/khugepaged.c:scan_sleep_millisecs_store",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/proc/root.c:proc_parse_param",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:parse_policy_line",
        "security/safesetid/securityfs.c:parse_policy_line",
        "security/device_cgroup.c:devcgroup_update_access",
        "security/device_cgroup.c:devcgroup_update_access",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/watchdog/watchdog_dev.c:nowayout_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpuidle/sysfs.c:store_state_disable",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_limit_min",
        "net/core/net-sysfs.c:bql_set_limit_max",
        "net/core/net-sysfs.c:bql_set_limit",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802304,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584846699,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:221",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtouint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_early_khz_setup",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/reboot.c:cpu_store",
        "kernel/sched/debug.c:sched_scaling_write",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/ksm.c:run_store",
        "mm/ksm.c:pages_to_scan_store",
        "mm/ksm.c:sleep_millisecs_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/memtest.c:parse_memtest",
        "mm/khugepaged.c:pages_to_scan_store",
        "mm/khugepaged.c:alloc_sleep_millisecs_store",
        "mm/khugepaged.c:scan_sleep_millisecs_store",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/proc/root.c:proc_parse_param",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/device_cgroup.c:devcgroup_update_access",
        "security/device_cgroup.c:devcgroup_update_access",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/parser.c:match_uint",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_probe.c:set_spurious_threshold",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/watchdog/watchdog_dev.c:nowayout_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpuidle/sysfs.c:store_state_disable",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "drivers/platform/x86/intel_pmc_core.c:etr3_store",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_limit_min",
        "net/core/net-sysfs.c:bql_set_limit_max",
        "net/core/net-sysfs.c:bql_set_limit",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846304,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585266721,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:222",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtouint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_early_khz_setup",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint_minmax",
        "kernel/reboot.c:cpu_store",
        "kernel/sched/debug.c:sched_scaling_write",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/ksm.c:stable_node_chains_prune_millisecs_store",
        "mm/ksm.c:run_store",
        "mm/ksm.c:pages_to_scan_store",
        "mm/ksm.c:sleep_millisecs_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/memtest.c:parse_memtest",
        "mm/khugepaged.c:pages_to_scan_store",
        "mm/khugepaged.c:alloc_sleep_millisecs_store",
        "mm/khugepaged.c:scan_sleep_millisecs_store",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/proc/root.c:proc_parse_param",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/device_cgroup.c:devcgroup_update_access",
        "security/device_cgroup.c:devcgroup_update_access",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/parser.c:match_uint",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/acpi/sysfs.c:enabled_store",
        "drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/ptp/ptp_sysfs.c:max_vclocks_store",
        "drivers/ptp/ptp_sysfs.c:n_vclocks_store",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/watchdog/watchdog_dev.c:nowayout_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpuidle/sysfs.c:store_state_disable",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "drivers/platform/x86/intel/pmc/core.c:etr3_store",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_limit_min",
        "net/core/net-sysfs.c:bql_set_limit_max",
        "net/core/net-sysfs.c:bql_set_limit",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585266288,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586110736,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:228",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_early_khz_setup",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint_minmax",
        "kernel/reboot.c:cpu_store",
        "kernel/sched/build_utility.c:sched_scaling_write",
        "kernel/sched/build_utility.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/ksm.c:stable_node_chains_prune_millisecs_store",
        "mm/ksm.c:run_store",
        "mm/ksm.c:pages_to_scan_store",
        "mm/ksm.c:sleep_millisecs_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/memtest.c:parse_memtest",
        "mm/khugepaged.c:pages_to_scan_store",
        "mm/khugepaged.c:alloc_sleep_millisecs_store",
        "mm/khugepaged.c:scan_sleep_millisecs_store",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/proc/root.c:proc_parse_param",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/device_cgroup.c:devcgroup_update_access",
        "security/device_cgroup.c:devcgroup_update_access",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/parser.c:match_uint",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/acpi/sysfs.c:enabled_store",
        "drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/ptp/ptp_sysfs.c:max_vclocks_store",
        "drivers/ptp/ptp_sysfs.c:n_vclocks_store",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/watchdog/watchdog_dev.c:nowayout_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpuidle/sysfs.c:store_state_disable",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "drivers/platform/x86/intel/pmc/core.c:etr3_store",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_limit_min",
        "net/core/net-sysfs.c:bql_set_limit_max",
        "net/core/net-sysfs.c:bql_set_limit",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586110736,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587096480,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:228",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_early_khz_setup",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint_minmax",
        "kernel/reboot.c:cpu_store",
        "kernel/sched/build_utility.c:sched_scaling_write",
        "kernel/sched/build_utility.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/vmscan.c:store_enabled",
        "mm/vmscan.c:store_min_ttl",
        "mm/backing-dev.c:strict_limit_store",
        "mm/backing-dev.c:max_ratio_fine_store",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_fine_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/ksm.c:stable_node_chains_prune_millisecs_store",
        "mm/ksm.c:run_store",
        "mm/ksm.c:pages_to_scan_store",
        "mm/ksm.c:sleep_millisecs_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/memtest.c:parse_memtest",
        "mm/khugepaged.c:pages_to_scan_store",
        "mm/khugepaged.c:alloc_sleep_millisecs_store",
        "mm/khugepaged.c:scan_sleep_millisecs_store",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/proc/root.c:proc_parse_param",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/device_cgroup.c:devcgroup_update_access",
        "security/device_cgroup.c:devcgroup_update_access",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/parser.c:match_uint",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/acpi/sysfs.c:enabled_store",
        "drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/ptp/ptp_sysfs.c:max_vclocks_store",
        "drivers/ptp/ptp_sysfs.c:n_vclocks_store",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/watchdog/watchdog_dev.c:nowayout_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpuidle/sysfs.c:store_state_disable",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "drivers/platform/x86/intel/pmc/core.c:etr3_store",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_limit_min",
        "net/core/net-sysfs.c:bql_set_limit_max",
        "net/core/net-sysfs.c:bql_set_limit",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587096480,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587356544,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:228",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:debug_alt",
        "arch/x86/kernel/tsc.c:tsc_early_khz_setup",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint_minmax",
        "kernel/reboot.c:cpu_store",
        "kernel/sched/build_utility.c:sched_scaling_write",
        "kernel/sched/build_utility.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_user.c:user_event_parse_field",
        "kernel/trace/trace_events_user.c:user_field_array_size",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "mm/vmscan.c:enabled_store",
        "mm/vmscan.c:min_ttl_ms_store",
        "mm/backing-dev.c:strict_limit_store",
        "mm/backing-dev.c:max_ratio_fine_store",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_fine_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/ksm.c:stable_node_chains_prune_millisecs_store",
        "mm/ksm.c:run_store",
        "mm/ksm.c:pages_to_scan_store",
        "mm/ksm.c:sleep_millisecs_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/memtest.c:parse_memtest",
        "mm/khugepaged.c:pages_to_scan_store",
        "mm/khugepaged.c:alloc_sleep_millisecs_store",
        "mm/khugepaged.c:scan_sleep_millisecs_store",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/proc/root.c:proc_parse_param",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/device_cgroup.c:devcgroup_update_access",
        "security/device_cgroup.c:devcgroup_update_access",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/parser.c:match_uint",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/acpi/sysfs.c:enabled_store",
        "drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/ptp/ptp_sysfs.c:max_vclocks_store",
        "drivers/ptp/ptp_sysfs.c:n_vclocks_store",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/watchdog/watchdog_dev.c:nowayout_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpuidle/sysfs.c:store_state_disable",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "drivers/platform/x86/intel/pmc/core.c:etr3_store",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_limit_min",
        "net/core/net-sysfs.c:bql_set_limit_max",
        "net/core/net-sysfs.c:bql_set_limit",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587356544,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587642864,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:228",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:debug_alt",
        "arch/x86/kernel/tsc.c:tsc_early_khz_setup",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint_minmax",
        "kernel/reboot.c:cpu_store",
        "kernel/sched/build_utility.c:sched_scaling_write",
        "kernel/sched/build_utility.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/trace/trace_events_synth.c:synth_field_string_size",
        "kernel/trace/trace_events_user.c:user_event_parse_field",
        "kernel/trace/trace_events_user.c:user_field_array_size",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "mm/vmscan.c:enabled_store",
        "mm/vmscan.c:min_ttl_ms_store",
        "mm/backing-dev.c:strict_limit_store",
        "mm/backing-dev.c:max_ratio_fine_store",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_fine_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/ksm.c:stable_node_chains_prune_millisecs_store",
        "mm/ksm.c:run_store",
        "mm/ksm.c:pages_to_scan_store",
        "mm/ksm.c:sleep_millisecs_store",
        "mm/memtest.c:parse_memtest",
        "mm/khugepaged.c:pages_to_scan_store",
        "mm/khugepaged.c:alloc_sleep_millisecs_store",
        "mm/khugepaged.c:scan_sleep_millisecs_store",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/proc/root.c:proc_parse_param",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/device_cgroup.c:devcgroup_update_access",
        "security/device_cgroup.c:devcgroup_update_access",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/parser.c:match_uint",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "lib/dynamic_debug.c:parse_linerange",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/acpi/sysfs.c:enabled_store",
        "drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/ptp/ptp_sysfs.c:max_vclocks_store",
        "drivers/ptp/ptp_sysfs.c:n_vclocks_store",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/watchdog/watchdog_dev.c:nowayout_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference",
        "drivers/cpuidle/sysfs.c:store_state_disable",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_limit_min",
        "net/core/net-sysfs.c:bql_set_limit_max",
        "net/core/net-sysfs.c:bql_set_limit",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587642864,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496160656,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/ata/libahci.c:ahci_led_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496160656,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229481552,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "lib/dynamic_debug.c:ddebug_exec_queries",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/ata/libahci.c:ahci_led_store",
        "drivers/mtd/mtdcore.c:mtd_bitflip_threshold_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229481552,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290424352,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/dlpar.c:dlpar_store",
        "arch/powerpc/platforms/pseries/dlpar.c:dlpar_store",
        "arch/powerpc/platforms/pseries/dlpar.c:dlpar_store",
        "arch/powerpc/platforms/pseries/dlpar.c:dlpar_store",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_probe",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290424352,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275212342,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_uint",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275212342,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244080,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244080,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584179280,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584179280,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584227840,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_set_hashsize",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227840,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int kstrtouint(const char * s, unsigned int base, unsigned int * res)
```

```json
{
  "name": "kstrtouint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584332672,
      "name": "kstrtouint",
      "external": true,
      "loc": "lib/kstrtox.c:217",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:max_threshold_occ_write",
        "arch/x86/mm/pkeys.c:setup_init_pkru",
        "arch/x86/mm/pkeys.c:init_pkru_write_file",
        "kernel/params.c:param_set_uint",
        "kernel/sched/cpufreq_schedutil.c:rate_limit_us_store",
        "kernel/power/hibernate.c:resumedelay_setup",
        "kernel/audit.c:audit_backlog_limit_set",
        "kernel/hung_task.c:hung_task_panic_setup",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "mm/backing-dev.c:max_ratio_store",
        "mm/backing-dev.c:min_ratio_store",
        "mm/slub.c:remote_node_defrag_ratio_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:order_store",
        "mm/memtest.c:parse_memtest",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "security/device_cgroup.c:devcgroup_access_write",
        "block/blk-sysfs.c:queue_io_timeout_store",
        "lib/kstrtox.c:kstrtouint_from_user",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/pwm/sysfs.c:unexport_store",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:duty_cycle_store",
        "drivers/pwm/sysfs.c:period_store",
        "drivers/acpi/sysfs.c:hotplug_enabled_store",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply",
        "drivers/xen/sys-hypervisor.c:pmu_features_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period",
        "drivers/scsi/scsi_sysfs.c:sdev_store_eh_timeout",
        "drivers/scsi/sd.c:max_medium_access_timeouts_store",
        "drivers/scsi/sd.c:protection_type_store",
        "drivers/usb/core/port.c:quirks_store",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softraw",
        "drivers/input/keyboard/atkbd.c:atkbd_set_softrepeat",
        "drivers/input/keyboard/atkbd.c:atkbd_set_set",
        "drivers/input/keyboard/atkbd.c:atkbd_set_scroll",
        "drivers/input/keyboard/atkbd.c:atkbd_set_extra",
        "drivers/thermal/thermal_sysfs.c:sustainable_power_store",
        "drivers/md/md.c:set_ro",
        "drivers/md/md.c:sync_max_store",
        "drivers/md/md.c:sync_min_store",
        "drivers/md/md.c:max_corrected_read_errors_store",
        "drivers/md/md.c:raid_disks_store",
        "drivers/md/md.c:layout_store",
        "drivers/md/md.c:ppl_size_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:errors_store",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/md/dm-stripe.c:stripe_ctr",
        "drivers/edac/edac_mc_sysfs.c:edac_set_poll_msec",
        "drivers/cpufreq/acpi-cpufreq.c:store_cpb",
        "drivers/cpufreq/intel_pstate.c:store_hwp_dynamic_boost",
        "drivers/clocksource/acpi_pm.c:parse_pmtmr",
        "net/core/utils.c:inet6_pton",
        "net/core/net-sysfs.c:bql_set_hold_time",
        "net/core/net-sysfs.c:bql_set",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/ipv4/tcp_metrics.c:set_tcpmhash_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584332672,
      "name": "kstrtouint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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

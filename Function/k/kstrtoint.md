# Function: <code>kstrtoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583048368,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:249",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/core.c:setup_relax_domain_level",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_adj_write",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_store",
        "drivers/base/power/sysfs.c:pm_qos_remote_wakeup_store",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/thermal/thermal_core.c:thermal_cooling_device_weight_store",
        "drivers/thermal/thermal_core.c:offset_store",
        "drivers/thermal/thermal_core.c:slope_store",
        "drivers/thermal/thermal_core.c:integral_cutoff_store",
        "drivers/thermal/thermal_core.c:k_d_store",
        "drivers/thermal/thermal_core.c:k_i_store",
        "drivers/thermal/thermal_core.c:k_pu_store",
        "drivers/thermal/thermal_core.c:k_po_store",
        "drivers/thermal/thermal_core.c:trip_point_hyst_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048368,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583342365,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:249",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/core.c:setup_relax_domain_level",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/base/power/sysfs.c:pm_qos_remote_wakeup_store",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_store",
        "drivers/thermal/thermal_core.c:thermal_cooling_device_weight_store",
        "drivers/thermal/thermal_core.c:offset_store",
        "drivers/thermal/thermal_core.c:slope_store",
        "drivers/thermal/thermal_core.c:integral_cutoff_store",
        "drivers/thermal/thermal_core.c:k_d_store",
        "drivers/thermal/thermal_core.c:k_i_store",
        "drivers/thermal/thermal_core.c:k_pu_store",
        "drivers/thermal/thermal_core.c:k_po_store",
        "drivers/thermal/thermal_core.c:emul_temp_store",
        "drivers/thermal/thermal_core.c:trip_point_hyst_store",
        "drivers/thermal/thermal_core.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342176,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583467741,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:245",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/core.c:setup_relax_domain_level",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/base/power/sysfs.c:pm_qos_remote_wakeup_store",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_store",
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583467552,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583489990,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:247",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/power/sysfs.c:pm_qos_remote_wakeup_store",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_store",
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489808,
      "name": "kstrtoint",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583671030,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_store",
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670848,
      "name": "kstrtoint",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583888822,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888624,
      "name": "kstrtoint",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583973062,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972864,
      "name": "kstrtoint",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584154278,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154080,
      "name": "kstrtoint",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584276902,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276704,
      "name": "kstrtoint",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584685894,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/fair.c:setup_sched_thermal_decay_shift",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_param_is_s32",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687040,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584803462,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:244",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/sched/fair.c:setup_sched_thermal_decay_shift",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_param_is_s32",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/dax/bus.c:create_store",
        "drivers/scsi/sd.c:max_retries_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584804608,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584847238,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:251",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/sched/fair.c:setup_sched_thermal_decay_shift",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_param_is_s32",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/pci/iov.c:sriov_vf_msix_count_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/dax/bus.c:create_store",
        "drivers/scsi/sd.c:max_retries_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584848384,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585267308,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:252",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:fail_store",
        "kernel/cpu.c:target_store",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/sched/fair.c:setup_sched_thermal_decay_shift",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_param_is_s32",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_async_depth_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/pci/iov.c:sriov_vf_msix_count_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/dax/bus.c:create_store",
        "drivers/scsi/sd.c:max_retries_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585268560,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586112192,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:259",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:fail_store",
        "kernel/cpu.c:target_store",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/sched/fair.c:setup_sched_thermal_decay_shift",
        "kernel/sched/build_utility.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_async_depth_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_prio_aging_expire_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/kstrtox.c:kstrtoint_from_user",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/pci/iov.c:sriov_vf_msix_count_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/block/loop.c:loop_set_hw_queue_depth",
        "drivers/dax/bus.c:create_store",
        "drivers/scsi/sd.c:max_retries_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/devfreq/devfreq.c:trans_stat_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586112192,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587098096,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:259",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:fail_store",
        "kernel/cpu.c:target_store",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/sched/fair.c:setup_sched_thermal_decay_shift",
        "kernel/sched/build_utility.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_async_depth_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_prio_aging_expire_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/kstrtox.c:kstrtoint_from_user",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/pci/iov.c:sriov_vf_msix_count_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/block/loop.c:loop_set_hw_queue_depth",
        "drivers/dax/bus.c:create_store",
        "drivers/scsi/sd.c:max_retries_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/devfreq/devfreq.c:trans_stat_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587098096,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587358160,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:259",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:fail_store",
        "kernel/cpu.c:target_store",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/sched/fair.c:setup_sched_thermal_decay_shift",
        "kernel/sched/build_utility.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_async_depth_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_prio_aging_expire_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/kstrtox.c:kstrtoint_from_user",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/pci/iov.c:sriov_vf_msix_count_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/block/loop.c:loop_set_hw_queue_depth",
        "drivers/dax/bus.c:create_store",
        "drivers/scsi/sd.c:max_retries_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/devfreq/devfreq.c:trans_stat_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587358160,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587644480,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:259",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:rootwait_timeout_setup",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:control_store",
        "kernel/cpu.c:fail_store",
        "kernel/cpu.c:target_store",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/sched/fair.c:setup_sched_thermal_decay_shift",
        "kernel/sched/build_utility.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:zswap_writeback_write",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction",
        "block/mq-deadline.c:deadline_fifo_batch_store",
        "block/mq-deadline.c:deadline_async_depth_store",
        "block/mq-deadline.c:deadline_front_merges_store",
        "block/mq-deadline.c:deadline_writes_starved_store",
        "block/mq-deadline.c:deadline_prio_aging_expire_store",
        "block/mq-deadline.c:deadline_write_expire_store",
        "block/mq-deadline.c:deadline_read_expire_store",
        "lib/kstrtox.c:kstrtoint_from_user",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/pci/iov.c:sriov_vf_msix_count_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/block/loop.c:loop_set_hw_queue_depth",
        "drivers/dax/bus.c:create_store",
        "drivers/scsi/sd.c:max_retries_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/cpufreq/cpufreq.c:store_local_boost",
        "drivers/devfreq/devfreq.c:trans_stat_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587644480,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496162428,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/bus/brcmstb_gisb.c:gisb_arb_set_timeout",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/resolver.c:of_resolve_phandles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496162200,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229483856,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/bus/brcmstb_gisb.c:gisb_arb_set_timeout",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/clk/ti/clk.c:ti_dt_clocks_register",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/resolver.c:of_resolve_phandles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229483540,
      "name": "kstrtoint",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290426612,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/powerpc/kernel/setup_64.c:check_smt_enabled",
        "arch/powerpc/kernel/fadump.c:fadump_register_store",
        "arch/powerpc/kernel/fadump.c:fadump_release_memory_store",
        "arch/powerpc/platforms/powernv/opal-powercap.c:powercap_store",
        "arch/powerpc/platforms/powernv/opal-psr.c:psr_store",
        "arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_freq_write",
        "arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/resolver.c:of_resolve_phandles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290426320,
      "name": "kstrtoint",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275213474,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store",
        "drivers/of/base.c:of_alias_scan",
        "drivers/of/resolver.c:of_resolve_phandles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275213338,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584245638,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/apic/io_apic.c:notimercheck",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/nvme/host/pci.c:io_queue_depth_set",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584245440,
      "name": "kstrtoint",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584180838,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/nvme/host/pci.c:io_queue_depth_set",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180640,
      "name": "kstrtoint",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584229398,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229200,
      "name": "kstrtoint",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoint(const char * s, unsigned int base, int * res)
```

```json
{
  "name": "kstrtoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584334230,
      "name": "kstrtoint",
      "external": true,
      "loc": "lib/kstrtox.c:248",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoint_from_user"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/mm/tlb.c:tlbflush_write_file",
        "kernel/cpu.c:write_cpuhp_fail",
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/params.c:param_set_int",
        "kernel/ksysfs.c:rcu_normal_store",
        "kernel/ksysfs.c:rcu_expedited_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/sched/topology.c:setup_relax_domain_level",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write_start",
        "kernel/events/core.c:perf_event_mux_interval_ms_store",
        "mm/ksm.c:max_page_sharing_store",
        "mm/memcontrol.c:memory_oom_group_write",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/base.c:sched_autogroup_write",
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/blk-sysfs.c:queue_poll_delay_store",
        "drivers/pwm/sysfs.c:enable_store",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/acpi/tables.c:acpi_parse_apic_instance",
        "drivers/tty/tty_io.c:tty_dev_name_to_number",
        "drivers/base/dd.c:deferred_probe_timeout_setup",
        "drivers/base/power/sysfs.c:pm_qos_no_power_off_store",
        "drivers/base/power/sysfs.c:pm_qos_latency_tolerance_us_store",
        "drivers/base/power/sysfs.c:pm_qos_resume_latency_us_store",
        "drivers/thermal/thermal_sysfs.c:weight_store",
        "drivers/thermal/thermal_sysfs.c:offset_store",
        "drivers/thermal/thermal_sysfs.c:slope_store",
        "drivers/thermal/thermal_sysfs.c:integral_cutoff_store",
        "drivers/thermal/thermal_sysfs.c:k_d_store",
        "drivers/thermal/thermal_sysfs.c:k_i_store",
        "drivers/thermal/thermal_sysfs.c:k_pu_store",
        "drivers/thermal/thermal_sysfs.c:k_po_store",
        "drivers/thermal/thermal_sysfs.c:emul_temp_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_hyst_store",
        "drivers/thermal/thermal_sysfs.c:trip_point_temp_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334032,
      "name": "kstrtoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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

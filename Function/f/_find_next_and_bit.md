# Function: <code>_find_next_and_bit</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int _find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int nbits, long unsigned int start)
```

```json
{
  "name": "_find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587065680,
      "name": "_find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:159",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:select_target_cpu",
        "drivers/base/power/domain_governor.c:cpu_power_down_ok",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/net-sysfs.c:store_rps_map",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending",
        "lib/cpumask.c:cpumask_any_and_distribute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587065680,
      "name": "_find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
long unsigned int _find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int nbits, long unsigned int start)
```

```json
{
  "name": "_find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587323776,
      "name": "_find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:168",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/smpboot.c:smp_park_other_cpus_in_init",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/xen/events/events_base.c:select_target_cpu",
        "drivers/base/power/domain_governor.c:cpu_power_down_ok",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending",
        "lib/cpumask.c:cpumask_any_and_distribute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323776,
      "name": "_find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long unsigned int _find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int nbits, long unsigned int start)
```

```json
{
  "name": "_find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587606720,
      "name": "_find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:168",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/cpu.c:cpu_down_maps_locked",
        "kernel/workqueue.c:wq_select_unbound_cpu",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:should_we_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/time/tick-sched.c:tick_nohz_dep_set",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/pmdomain/governor.c:cpu_power_down_ok",
        "drivers/xen/events/events_base.c:select_target_cpu",
        "drivers/powercap/idle_inject.c:idle_inject_wakeup",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending",
        "lib/cpumask.c:cpumask_any_and_distribute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587606720,
      "name": "_find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
long unsigned int _find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int nbits, long unsigned int start)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

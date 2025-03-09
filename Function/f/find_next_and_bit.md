# Function: <code>find_next_and_bit</code>

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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583867792,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:89",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867792,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953072,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:89",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953072,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584133088,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:85",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133088,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255488,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:85",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255488,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584663456,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:93",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_local_spread",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663456,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780816,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:95",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_local_spread",
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780816,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585073271,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:52",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589244284,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:52",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585519959,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:52",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589969053,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:52",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586671958,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:60",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute",
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591506694,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:60",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593719831,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:60",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579121170,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539432,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579968178,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580132461,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580246966,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:find_idlest_group_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580310353,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/sched/build_policy.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580350264,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580914575,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581346436,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586456298,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589161450,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589451661,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:select_target_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590439902,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain_governor.c:cpu_power_down_ok"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593032535,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593283985,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593574439,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595655047,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595751386,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:78",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579121723,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495384,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:smp_park_other_cpus_in_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552259,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580018482,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580194717,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580312993,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:find_idlest_group_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580340606,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/sched/build_policy.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580415384,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999854,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440616,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586706234,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589454762,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589751197,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:select_target_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590759566,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain_governor.c:cpu_power_down_ok"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593484455,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593737346,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594044543,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596163975,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596275690,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579147579,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:__xen_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579580035,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897773,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpu_down_maps_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580054548,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_select_unbound_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580242333,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580365556,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:should_we_balance",
        "kernel/sched/fair.c:find_busiest_queue",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:find_idlest_group_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580392322,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/sched/build_policy.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580470936,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059136,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_dep_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095998,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581549896,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586979370,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589762746,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590004622,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "drivers/pmdomain/governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pmdomain/governor.c:cpu_power_down_ok"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590090221,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:select_target_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594231703,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594518464,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594834831,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597038311,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597160522,
      "name": "find_next_and_bit",
      "external": false,
      "loc": "include/linux/find.h:83",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_any_and_distribute"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496133888,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:85",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496133888,
      "name": "find_next_and_bit",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229457300,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:85",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229457300,
      "name": "find_next_and_bit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290391104,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:85",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290391104,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275191506,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:85",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275191506,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224224,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:85",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224224,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159440,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:85",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159440,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207984,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:85",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207984,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```

```json
{
  "name": "find_next_and_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312544,
      "name": "find_next_and_bit",
      "external": true,
      "loc": "lib/find_bit.c:85",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue",
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312544,
      "name": "find_next_and_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int * addr1, const long unsigned int * addr2, long unsigned int size, long unsigned int offset)
```
</details>
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

# Function: <code>proc_dointvec_minmax</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579405472,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2288",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/events/core.c:perf_proc_update_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/compaction.c:sysctl_extfrag_handler",
        "fs/pipe.c:pipe_proc_fn",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405472,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579416681,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2434",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/compaction.c:sysctl_extfrag_handler",
        "fs/pipe.c:pipe_proc_fn",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/addrconf.c:addrconf_sysctl_hop_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416352,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579436985,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2419",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/compaction.c:sysctl_extfrag_handler",
        "fs/pipe.c:pipe_proc_fn",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436656,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579426569,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2576",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/compaction.c:sysctl_extfrag_handler",
        "fs/pipe.c:pipe_proc_fn",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426240,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579453577,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2566",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/compaction.c:sysctl_extfrag_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453248,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579468246,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2580",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/compaction.c:sysctl_extfrag_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467792,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501814,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2637",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/compaction.c:sysctl_extfrag_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501344,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520675,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2716",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519584,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579546755,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2718",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545664,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579581299,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:959",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change",
        "kernel/sysctl.c:bpf_stats_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/sched/topology.c:sched_energy_aware_handler",
        "kernel/sched/topology.c:sched_energy_aware_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579600,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579562915,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:958",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change",
        "kernel/sysctl.c:bpf_stats_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/sched/topology.c:sched_energy_aware_handler",
        "kernel/sched/topology.c:sched_energy_aware_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561216,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579568458,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:970",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change",
        "kernel/sysctl.c:bpf_unpriv_handler",
        "kernel/sysctl.c:bpf_stats_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/topology.c:sched_energy_aware_handler",
        "kernel/sched/topology.c:sched_energy_aware_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565296,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641466,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:1014",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change",
        "kernel/sysctl.c:bpf_unpriv_handler",
        "kernel/sysctl.c:bpf_stats_handler"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/topology.c:sched_energy_aware_handler",
        "kernel/sched/topology.c:sched_energy_aware_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/compaction.c:compaction_proactiveness_sysctl_handler",
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635280,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579736827,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:883",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/build_utility.c:sched_energy_aware_handler",
        "kernel/sched/build_utility.c:sched_energy_aware_handler",
        "kernel/printk/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/bpf/syscall.c:bpf_unpriv_handler",
        "kernel/bpf/syscall.c:bpf_unpriv_handler",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/compaction.c:compaction_proactiveness_sysctl_handler",
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "mm/hugetlb_vmemmap.c:hugetlb_optimize_vmemmap_handler",
        "mm/hugetlb_vmemmap.c:hugetlb_optimize_vmemmap_handler",
        "fs/exec.c:proc_dointvec_minmax_coredump",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax_orphans",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731232,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579867771,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:890",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/build_utility.c:sched_energy_aware_handler",
        "kernel/sched/build_utility.c:sched_energy_aware_handler",
        "kernel/printk/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/bpf/syscall.c:bpf_unpriv_handler",
        "kernel/bpf/syscall.c:bpf_unpriv_handler",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/compaction.c:compaction_proactiveness_sysctl_handler",
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/exec.c:proc_dointvec_minmax_coredump",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax_orphans",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866096,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917707,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:868",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/build_utility.c:sched_energy_aware_handler",
        "kernel/sched/build_utility.c:sched_energy_aware_handler",
        "kernel/printk/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_mfd_noexec_dointvec_minmax",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/bpf/syscall.c:bpf_unpriv_handler",
        "kernel/bpf/syscall.c:bpf_unpriv_handler",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/compaction.c:proc_dointvec_minmax_warn_RT_change",
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "fs/exec.c:proc_dointvec_minmax_coredump",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax_orphans",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916176,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579956955,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:868",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/build_policy.c:sched_rt_handler",
        "kernel/printk/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_mfd_noexec_dointvec_minmax",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/bpf/syscall.c:bpf_unpriv_handler",
        "kernel/bpf/syscall.c:bpf_unpriv_handler",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/bpf/syscall.c:bpf_stats_handler",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_event_max_sample_rate_handler",
        "kernel/events/core.c:perf_event_max_sample_rate_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/compaction.c:proc_dointvec_minmax_warn_RT_change",
        "mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "fs/exec.c:proc_dointvec_minmax_coredump",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax_orphans",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955424,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490695632,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2718",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/arm64/kernel/armv8_deprecated.c:emulation_proc_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490694136,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224763368,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2718",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224761976,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283522148,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2718",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283520544,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271427458,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2718",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271426424,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520419,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2718",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519328,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579449219,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2718",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448128,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520339,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2718",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519248,
      "name": "proc_dointvec_minmax",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dointvec_minmax(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dointvec_minmax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579553299,
      "name": "proc_dointvec_minmax",
      "external": true,
      "loc": "kernel/sysctl.c:2718",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ],
      "caller_func": [
        "arch/x86/kernel/itmt.c:sched_itmt_update_handler",
        "kernel/fork.c:sysctl_max_threads",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:sched_proc_update_handler",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/kprobes.c:proc_kprobes_optimization_handler",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/watchdog.c:proc_watchdog_common",
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/core.c:perf_proc_update_handler",
        "kernel/events/callchain.c:perf_event_max_stack_handler",
        "mm/page-writeback.c:dirty_ratio_handler",
        "mm/page-writeback.c:dirty_background_ratio_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler",
        "mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler",
        "mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler",
        "mm/page_alloc.c:watermark_scale_factor_sysctl_handler",
        "mm/page_alloc.c:watermark_boost_factor_sysctl_handler",
        "mm/page_alloc.c:min_free_kbytes_sysctl_handler",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "ipc/ipc_sysctl.c:proc_ipc_auto_msgmni",
        "ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax",
        "ipc/mq_sysctl.c:proc_mq_dointvec_minmax",
        "security/yama/yama_lsm.c:yama_dointvec_minmax",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable",
        "net/core/neighbour.c:neigh_proc_dointvec_unres_qlen",
        "net/core/neighbour.c:neigh_proc_dointvec_zero_intmax",
        "net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy",
        "net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range",
        "net/ipv6/addrconf.c:addrconf_sysctl_mtu",
        "net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552208,
      "name": "proc_dointvec_minmax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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

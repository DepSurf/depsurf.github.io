# Function: <code>__bitmap_subset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010848,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:222",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:add_del_listener",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010848,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301360,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:224",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:add_del_listener",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301360,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420400,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:224",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420400,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441536,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:224",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/topology.c:build_sched_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441536,
      "name": "__bitmap_subset",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621472,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:226",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621472,
      "name": "__bitmap_subset",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837824,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:223",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837824,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921456,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:220",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921456,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584101264,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:220",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101264,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224048,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224048,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630096,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:319",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:activate_reserved",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/cpuhotplug.c:hk_should_isolate",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/oom_kill.c:constrained_alloc",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630096,
      "name": "__bitmap_subset",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584749152,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:319",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:activate_reserved",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/cpuhotplug.c:hk_should_isolate",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/oom_kill.c:constrained_alloc",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584749152,
      "name": "__bitmap_subset",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777488,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:321",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/oom_kill.c:constrained_alloc",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777488,
      "name": "__bitmap_subset",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207504,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:321",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/oom_kill.c:constrained_alloc",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207504,
      "name": "__bitmap_subset",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043360,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:321",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/taskstats.c:add_del_listener",
        "mm/oom_kill.c:constrained_alloc",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043360,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
bool __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587026144,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:321",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/taskstats.c:add_del_listener",
        "mm/oom_kill.c:constrained_alloc",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026144,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
bool __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587281136,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:321",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/cpumask.c:bpf_cpumask_subset",
        "mm/oom_kill.c:constrained_alloc",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587281136,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
bool __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587569872,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:310",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:prstate_housekeeping_conflict",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:remote_partition_disable",
        "kernel/cgroup/cpuset.c:tasks_nocpu_error",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/cpumask.c:bpf_cpumask_subset",
        "mm/oom_kill.c:constrained_alloc",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569872,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496097792,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "drivers/base/arch_topology.c:cpu_coregroup_mask",
        "drivers/base/arch_topology.c:cpu_coregroup_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496097792,
      "name": "__bitmap_subset",
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229424640,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229424640,
      "name": "__bitmap_subset",
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290342144,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/sysdev/xics/xics-common.c:xics_get_irq_server",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290342144,
      "name": "__bitmap_subset",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275166014,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275166014,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192784,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192784,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584128000,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128000,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584176544,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176544,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int __bitmap_subset(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_subset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584280880,
      "name": "__bitmap_subset",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/taskstats.c:add_del_listener",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280880,
      "name": "__bitmap_subset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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

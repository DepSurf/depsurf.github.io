# Function: <code>__bitmap_and</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010432,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:153",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:workqueue_cpu_up_callback",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:guarantee_online_cpus",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010432,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583300928,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:155",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300928,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583419968,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:155",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_set_nodemask",
        "mm/mempolicy.c:mpol_set_nodemask",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583419968,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441040,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:155",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:build_sched_domain",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441040,
      "name": "__bitmap_and",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620976,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:157",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620976,
      "name": "__bitmap_and",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837392,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:154",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837392,
      "name": "__bitmap_and",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921024,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:151",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921024,
      "name": "__bitmap_and",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584100832,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:151",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584100832,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223616,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223616,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584629616,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:238",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sd_init",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584629616,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584748672,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:238",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sd_init",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748672,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777008,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sd_init",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/powercap/dtpm_cpu.c:get_pd_power_uw",
        "drivers/powercap/dtpm_cpu.c:set_pd_power_limit",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777008,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207024,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/cpupri.c:cpupri_find_fitness",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sd_init",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/powercap/dtpm_cpu.c:get_pd_power_uw",
        "drivers/powercap/dtpm_cpu.c:set_pd_power_limit",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207024,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042736,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/net/phy/phy_device.c:__genphy_config_aneg",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042736,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
bool __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025424,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/memory-tiers.c:establish_demotion_targets",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025424,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
bool __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587280416,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:240",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_fork",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/trace/trace_osnoise.c:start_per_cpu_kthreads",
        "kernel/bpf/cpumask.c:bpf_cpumask_and",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/memory-tiers.c:establish_demotion_targets",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:alloc_nodes_groups",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587280416,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
bool __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587569152,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:229",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel",
        "kernel/workqueue.c:restrict_unbound_cpumask",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_pod_cpumask",
        "kernel/workqueue.c:wq_calc_pod_cpumask",
        "kernel/workqueue.c:wq_calc_pod_cpumask",
        "kernel/workqueue.c:wqattrs_actualize_cpumask",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/build_policy.c:cpudl_find",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_fork",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:partition_xcpus_del",
        "kernel/cgroup/cpuset.c:reset_partition_data",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/trace/trace_osnoise.c:start_per_cpu_kthreads",
        "kernel/bpf/cpumask.c:bpf_cpumask_and",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/memory-tiers.c:establish_demotion_targets",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:alloc_nodes_groups",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569152,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496097320,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/fpsimd.c:sve_update_vq_map",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "mm/sparse.c:section_deactivate",
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496097320,
      "name": "__bitmap_and",
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229424120,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229424120,
      "name": "__bitmap_and",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290341456,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/numa.c:mem_topology_setup",
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online",
        "arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_online",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290341456,
      "name": "__bitmap_and",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275165532,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275165532,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192352,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192352,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127568,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127568,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584176112,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176112,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __bitmap_and(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_and",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584280448,
      "name": "__bitmap_and",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/cpupri.c:cpupri_find",
        "kernel/sched/cpudeadline.c:cpudl_find",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/smp.c:smp_call_function_many",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/watchdog.c:proc_watchdog_update",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280448,
      "name": "__bitmap_and",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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

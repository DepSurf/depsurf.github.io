# Function: <code>bitmap_and</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578983436,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193312,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213786,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579465280,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:workqueue_cpu_up_callback",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557608,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:build_sched_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648332,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579649403,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746299,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579881552,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579909269,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003123,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:guarantee_online_cpus",
        "kernel/cpuset.c:guarantee_online_mems",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580136374,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459733,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813662,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_set_nodemask",
        "mm/mempolicy.c:mpol_set_nodemask",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583815075,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585864541,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578980147,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196889,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214506,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579502518,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572150,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663896,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664987,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579768712,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911062,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938994,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580045602,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580170518,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580535198,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939564,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_set_nodemask",
        "mm/mempolicy.c:mpol_set_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586266066,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578982111,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208584,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226219,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579523278,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579597300,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579620775,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579688458,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579689591,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795689,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827190,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579941795,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579970188,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083515,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580210454,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580341411,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580597979,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581007095,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/mempolicy.c:mpol_set_nodemask",
        "mm/mempolicy.c:mpol_set_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586470284,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578991769,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121337,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206118,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223152,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579511116,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578162,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579633145,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674489,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675571,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579681577,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793429,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827108,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950041,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975522,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580089304,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218591,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580354937,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580627771,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581053743,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586594937,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578994717,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135276,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221832,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579538044,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579607858,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663625,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579705225,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579706211,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717453,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827093,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862909,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579995739,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022002,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580142961,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580268678,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408651,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580708752,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581164879,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585533575,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587078255,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578998615,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144616,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233707,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579564460,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579638085,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579696490,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738138,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739203,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749079,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860919,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579895959,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580047835,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580076069,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580201875,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580328917,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469652,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580840416,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311590,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585037076,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777216,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587376018,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:262",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578996215,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210153,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258123,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601692,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675765,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579735354,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579777898,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579778963,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579789111,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579907881,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579942993,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580094667,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123381,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580253291,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580382181,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525732,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580909360,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393142,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585148804,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585910736,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586549128,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586551882,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586555824,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587555954,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579004942,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223877,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272210,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579624988,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579707701,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764643,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579805562,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579806590,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579816826,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943251,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981776,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580138534,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580168872,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580295667,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580434885,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582156,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581007292,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505283,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522613,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585355348,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586150400,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586794053,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586800332,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586803111,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586808747,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587830868,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:263",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579006446,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226187,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274578,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651020,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749797,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579807283,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853130,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854156,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579864871,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579993475,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032012,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580186678,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580216808,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580344019,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580483653,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580629260,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063858,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569689,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587195,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585493876,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586298976,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586940389,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586946188,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586950567,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586957131,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588035699,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579011525,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243976,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302314,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579682522,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579785605,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579848397,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579892236,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579893468,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905911,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580040819,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580082803,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580251462,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580284760,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580429453,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580568517,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730237,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244161,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581783056,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799172,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:clear_subsection_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586213024,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587069104,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587757699,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587763068,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587767895,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774364,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_config_advert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587782798,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "drivers/net/phy/linkmode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588897264,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589896686,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579014469,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236824,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307658,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579662426,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776430,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579840317,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579886857,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888023,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900832,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580024019,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065379,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580235286,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580268280,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416989,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580556389,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580719576,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581285186,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581834357,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581847076,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:clear_subsection_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586332896,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587153600,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817267,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587822252,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587827079,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587833548,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_config_advert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587841262,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/net/phy/linkmode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588909824,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589570372,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589935733,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579014547,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183471,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579236936,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309674,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669020,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579785022,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579848977,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896044,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897179,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579909909,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580024707,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580066013,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580240598,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580272620,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580419773,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559701,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724666,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303250,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581865201,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877970,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586206544,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587041072,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587696628,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587701580,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587706471,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587712652,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_config_advert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587720686,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/net/phy/linkmode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588797398,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589048203,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/powercap/dtpm_cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/dtpm_cpu.c:get_pd_power_uw",
        "drivers/powercap/dtpm_cpu.c:set_pd_power_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589468355,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589844141,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features"
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
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579032883,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217711,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579275432,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360906,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746038,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579879454,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579954193,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010836,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580012235,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580028818,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580157084,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199483,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391232,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580424514,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580583085,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580729637,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904886,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547848,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582156737,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169570,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586712368,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587608834,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588288212,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588293212,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588298512,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588305244,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_config_advert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588313598,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "drivers/net/phy/linkmode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589489799,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589765259,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "drivers/powercap/dtpm_cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/dtpm_cpu.c:get_pd_power_uw",
        "drivers/powercap/dtpm_cpu.c:set_pd_power_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590207051,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590606511,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:287",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features"
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
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579053364,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594662302,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329227,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421513,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579850270,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579995745,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580068673,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580105835,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580201873,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580302881,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580352564,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580609297,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580647311,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580784150,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580942069,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140459,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900168,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582611990,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582627392,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587007853,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587981984,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588948235,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589670949,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589679199,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589685664,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589701291,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__genphy_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589702302,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "drivers/net/phy/linkmode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590972437,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591781948,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592227079,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:306",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593871713,
      "name": "bitmap_and.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool bitmap_and(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579084447,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596396738,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396203,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504985,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990904,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580157537,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setaffinity"
      ]
    },
    {
      "addr": 18446744071580239117,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580279147,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580392882,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580515137,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574860,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580873850,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580914219,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067798,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581235685,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453394,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334174,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135222,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583151744,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583264615,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588177522,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589352992,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589940912,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:try_to_generate_entropy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590463680,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591281029,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591289823,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591298818,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591314955,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_config_advert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591318334,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "drivers/net/phy/linkmode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592676839,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593574641,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594058759,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:320",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087664,
      "name": "bitmap_and",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool bitmap_and(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579084655,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596927698,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407081,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517257,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619517699,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044616,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206369,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setaffinity"
      ]
    },
    {
      "addr": 18446744071580305013,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580346436,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580461262,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580588033,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957146,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999381,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158150,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330949,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550898,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561474,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:start_per_cpu_kthreads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374197,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_and"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582535390,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583345542,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583362080,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583484967,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588179663,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:alloc_nodes_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588453554,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589650624,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590250192,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:try_to_generate_entropy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590786608,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591637718,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591649804,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591657490,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591675976,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:genphy_config_advert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591677390,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "drivers/net/phy/linkmode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593107581,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594055279,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:rps_cpumask_housekeeping",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594437223,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:318",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143600,
      "name": "bitmap_and",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool bitmap_and(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579110447,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597853426,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435737,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545977,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:activate_managed",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621814643,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621819103,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:restrict_unbound_cpumask",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_pod_cpumask",
        "kernel/workqueue.c:wq_calc_pod_cpumask",
        "kernel/workqueue.c:wq_calc_pod_cpumask",
        "kernel/workqueue.c:wqattrs_actualize_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580254689,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setaffinity"
      ]
    },
    {
      "addr": 18446744071580357663,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_energy_efficient_cpu",
        "kernel/sched/fair.c:select_idle_capacity",
        "kernel/sched/fair.c:select_idle_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580401166,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580520932,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:cpupri_find_fitness",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580652385,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621852067,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048730,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095525,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263654,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:partition_xcpus_del",
        "kernel/cgroup/cpuset.c:reset_partition_data",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437461,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663122,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673682,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:start_per_cpu_kthreads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541525,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_and"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582704205,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583581637,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583598532,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677815,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588470511,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:alloc_nodes_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588750514,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589961056,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590591184,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:try_to_generate_entropy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591129408,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592378310,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592391052,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592399778,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_check_downshift",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592418376,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:genphy_config_advert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592419790,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/net/phy/linkmode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/linkmode.c:linkmode_resolve_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593860397,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594845775,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:rps_cpumask_housekeeping",
        "net/core/net-sysfs.c:rps_cpumask_housekeeping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595239577,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189024,
      "name": "bitmap_and",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490187324,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:sve_update_vq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490268072,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/arm64/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/alternative.c:__apply_alternatives"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490823948,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490928240,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490987316,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491048424,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491049936,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491062808,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491183708,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491236804,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491412060,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491455284,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491607808,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491759848,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491933504,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492421664,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493006116,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493025240,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498010632,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499131804,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpulist",
        "drivers/base/node.c:node_read_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499927572,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499928580,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499935412,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499943312,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501303520,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501783468,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/perf/hisilicon/hisi_uncore_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501795772,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224857140,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3224947808,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3224996996,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 3225054292,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 3225055640,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 3225065220,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 3225206632,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3225249848,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225407900,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 3225441544,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 3225569932,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 3225709532,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3225867684,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226306032,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 3230789020,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 3232472056,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 3232473052,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 3232479004,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 3232486016,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233791664,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 3233829000,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/cpuidle/coupled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/coupled.c:coupled_cpu_online",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_register_device",
        "drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled",
        "drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302444912,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:mem_topology_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283393716,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/powerpc/perf/imc-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online",
        "arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283658576,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283781584,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283856512,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283925088,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283926656,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283941976,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284085692,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284136696,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284360372,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284406036,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284592172,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284801836,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285031904,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285691892,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286434760,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286454480,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291366208,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292322740,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293242488,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293246204,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293255088,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293265596,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294834984,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294863608,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/cpufreq/powernv-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271497538,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271564780,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271599628,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271644928,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271646108,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271654434,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271731284,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271767348,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271911334,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272011940,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272082344,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_cpumask",
        "kernel/watchdog.c:proc_watchdog_thresh",
        "kernel/watchdog.c:proc_watchdog_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272208864,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272510106,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275930460,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277013488,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277014610,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277020514,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277027104,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579006798,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225035,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273282,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579627324,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725749,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579783059,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825482,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826508,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579837223,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579962211,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580000748,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155478,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185608,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580312819,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580452453,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580598060,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032706,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538425,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555931,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585255956,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586062224,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586697397,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586703196,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586707575,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586714139,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587660691,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579159963,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208626,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555676,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654309,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579713859,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760058,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761084,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579771799,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900051,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579939420,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604735716,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580101590,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580133091,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580260147,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580399525,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580544540,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978786,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480185,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497579,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585208580,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585908176,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586565733,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586571516,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586575895,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586582443,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587434563,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579006382,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226107,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274482,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579624604,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712501,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767651,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579813498,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579814524,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825239,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579953747,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579992284,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580146950,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580177080,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580304067,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580443701,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580589308,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023906,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529737,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547243,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585444276,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586247872,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586894949,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586900748,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586905127,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586911691,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587991843,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_and",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579009326,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231515,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280548,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579658252,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579757479,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579815683,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579858618,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579859644,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870369,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580000129,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039020,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580198932,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580229272,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580358510,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580499333,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:proc_watchdog_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646204,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581085922,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596403,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612363,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585552212,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586357888,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_read_cpumap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587001333,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587007132,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587011511,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587018075,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588107267,
      "name": "bitmap_and",
      "external": false,
      "loc": "include/linux/bitmap.h:267",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool bitmap_and(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
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

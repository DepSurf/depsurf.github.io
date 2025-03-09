# Function: <code>bitmap_equal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579175031,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579194399,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215782,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465371,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579534198,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:partition_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579878816,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880827,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003633,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580458899,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580820596,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583917278,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:255",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
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
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579175547,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579195022,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215446,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497017,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575689,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908884,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910363,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580045644,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580534419,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899421,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580946016,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584140116,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584248441,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579185978,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206621,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227854,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517291,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601768,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071579939332,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579940827,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083585,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342169,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580599466,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580967821,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581005036,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584320612,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584430037,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:265",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565664,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579184884,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204282,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225550,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579505353,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579566912,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579686231,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579947252,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948747,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580089377,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580354891,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580629498,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581014792,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058234,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584400420,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584514396,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
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
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579018750,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200535,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579241102,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532079,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579596656,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716966,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602748575,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579992948,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994459,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580143034,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408596,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710538,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581123796,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581169264,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584806756,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584924429,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:281",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579021888,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024812,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579212423,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253686,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579559567,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579628284,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579748616,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071602920968,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044685,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580046612,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580201955,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469627,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842202,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266868,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310366,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585037079,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585156121,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:312",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740512,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579024774,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579028916,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236103,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277481,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579596783,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665916,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788648,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071604718674,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580091533,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093444,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580253438,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525707,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580911658,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349950,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392302,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585148807,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585266937,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586547536,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586563350,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780272,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579033172,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036146,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249560,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291798,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579618199,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697148,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579816344,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071604819482,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580135389,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137316,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580305863,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582114,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581008586,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460769,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581503809,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585355351,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477308,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586796783,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586814380,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807936,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579035492,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038466,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269260,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579646191,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579737982,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579864274,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071604853891,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580183533,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185460,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580354727,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580629218,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063884,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524864,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568209,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585493879,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585618020,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586942743,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586960588,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855456,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579046110,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047970,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579297244,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676990,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579774014,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579904948,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:init_overlap_sched_group",
        "kernel/sched/topology.c:build_balance_mask",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071609184327,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580248763,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-common.c:tick_check_percpu",
        "kernel/time/tick-common.c:tick_check_percpu",
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580250609,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580427400,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580729203,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732480,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787719,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586213027,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586341498,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587755121,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587778537,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589891395,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589896548,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895536,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049529,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051298,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302492,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656814,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579763626,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899860,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:init_overlap_sched_group",
        "kernel/sched/topology.c:build_balance_mask",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071612249950,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580232667,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-common.c:tick_check_percpu",
        "kernel/time/tick-common.c:tick_check_percpu",
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580234433,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580414888,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718531,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780128,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581828031,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586332899,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591453655,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587814689,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587838569,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589930531,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589935601,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features",
        "net/ethtool/features.c:ethnl_set_features"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890240,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579052382,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056482,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579305356,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663276,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579771338,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908944,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071614391480,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580238282,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580239553,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416488,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723652,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807725,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581859167,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586206547,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591395433,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587694187,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587718713,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589838501,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589843991,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:331",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898928,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579073223,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077675,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579353388,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746086,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862070,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580027769,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071615325620,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580387624,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580389615,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580580871,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904265,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582093037,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582154961,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/mempolicy.c:mpol_rebind_task"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586712371,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592440225,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588285579,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588311625,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590601253,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590606343,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:337",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014160,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579098343,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105712,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579415624,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579850322,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579977452,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580200811,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580605302,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580607819,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781786,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140441,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582619497,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__mpol_equal",
        "mm/mempolicy.c:__mpol_equal"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587981987,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594308217,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589673583,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589699872,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592221495,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592226881,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:356",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/features.c:ethnl_set_features"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593880445,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579134759,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142789,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579498472,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990954,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580138037,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627771931,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580869014,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871835,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581064937,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453339,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583143401,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__mpol_equal",
        "mm/mempolicy.c:__mpol_equal",
        "mm/mempolicy.c:mpol_rebind_task"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589352995,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589540006,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591285051,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591317152,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594051848,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594058561,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:370",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579135357,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143445,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579510648,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044666,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580217156,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619533531,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952774,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955595,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155305,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550843,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374389,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_equal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583353837,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__mpol_equal",
        "mm/mempolicy.c:__mpol_equal",
        "mm/mempolicy.c:mpol_rebind_task"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589650627,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589841302,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635246,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591665245,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594430788,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "net/ethtool/features.c",
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
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579161855,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172821,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579538536,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081253,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_unbound_exclude_cpumask",
        "kernel/workqueue.c:wqattrs_equal",
        "kernel/workqueue.c:wqattrs_equal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580265956,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621832473,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044358,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581047179,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260857,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663067,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581757373,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call",
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541717,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_equal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583589613,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__mpol_equal",
        "mm/mempolicy.c:__mpol_equal",
        "mm/mempolicy.c:mpol_rebind_task"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589961059,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:private_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590178374,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592375838,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592407517,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595233044,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:345",
      "file": "net/ethtool/features.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490817056,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490916184,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491062144,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510887372,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491407240,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491410564,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491614056,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491932816,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492421676,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492951308,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493004148,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493025260,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498010636,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498091596,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/soc/fsl/qbman/qman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499925964,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499946744,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491063744,
      "name": "bitmap_equal.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224676720,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/arm/mach-tegra/pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-tegra/pm.c:tegra_set_cpu_in_lp2"
      ],
      "caller_func": []
    },
    {
      "addr": 3224850812,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 3224934200,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 3225064572,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 3243374264,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3225403896,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-common.c:tick_check_percpu",
        "kernel/time/tick-common.c:tick_check_percpu",
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3225406664,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3225571288,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 3225868204,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226306032,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 3226734324,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 3230789024,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 3232470404,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232488964,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233830600,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/cpuidle/coupled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/coupled.c:cpuidle_coupled_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225057360,
      "name": "bitmap_equal.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282278936,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/powerpc/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/irq.c:irq_choose_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282421312,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/powerpc/kernel/rtas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282516844,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282927620,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/powerpc/sysdev/xics/xics-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xics/xics-common.c:xics_get_irq_server"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283649664,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283764668,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283941236,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302520844,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284353824,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284358212,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284606020,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285031868,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285691924,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286364880,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286435824,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286454488,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291366212,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293243640,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293271088,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283942580,
      "name": "bitmap_equal.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271491452,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271553850,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271653898,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270627574,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271884236,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272016272,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272208794,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272509006,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272866030,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275930464,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277010888,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277028642,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579035844,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038818,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267964,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579622495,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714606,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579836626,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071604759059,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580152733,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154260,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580323527,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580598018,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032732,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493600,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536945,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585255959,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585379668,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586699751,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586717596,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827808,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578968684,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971628,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203388,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579550857,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642494,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579771202,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071604726793,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580098253,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100372,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270807,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580544498,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978812,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435840,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478705,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585208583,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586568103,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586585900,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587572704,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel_mgmt.c:init_vp_index"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762384,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579035428,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038402,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269164,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579619775,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579701870,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824642,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071604836535,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580143805,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580145732,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314775,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580589266,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023932,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484912,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581528257,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585444279,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585568420,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586897303,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586915148,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815824,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038996,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042050,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274764,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:apic_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579653430,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579745246,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579869762,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071604857961,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580195757,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197716,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580369733,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646162,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581085948,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581549212,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593537,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585552215,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585676388,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587003687,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587021532,
      "name": "bitmap_equal",
      "external": false,
      "loc": "include/linux/bitmap.h:317",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860944,
      "name": "bitmap_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bitmap_equal(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
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

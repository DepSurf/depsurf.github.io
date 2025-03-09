# Function: <code>__bitmap_equal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010256,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:45",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010256,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583300736,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:47",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:rebuild_sched_domains_locked",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300736,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583419776,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:47",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
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
        "kernel/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "mm/mempolicy.c:mpol_rebind_policy",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583419776,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583440848,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:47",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583440848,
      "name": "__bitmap_equal",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620784,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:49",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620784,
      "name": "__bitmap_equal",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837232,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:49",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837232,
      "name": "__bitmap_equal",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583920864,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920864,
      "name": "__bitmap_equal",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584100672,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data",
        "drivers/net/phy/phy.c:phy_speed_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584100672,
      "name": "__bitmap_equal",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223456,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223456,
      "name": "__bitmap_equal",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584629472,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:init_overlap_sched_group",
        "kernel/sched/topology.c:build_balance_mask",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-common.c:tick_check_percpu",
        "kernel/time/tick-common.c:tick_check_percpu",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584629472,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584748528,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:init_overlap_sched_group",
        "kernel/sched/topology.c:build_balance_mask",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-common.c:tick_check_percpu",
        "kernel/time/tick-common.c:tick_check_percpu",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748528,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776864,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:48",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776864,
      "name": "__bitmap_equal",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585206880,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:48",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585206880,
      "name": "__bitmap_equal",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042528,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:48",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down",
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042528,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
bool __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025184,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:48",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
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
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down",
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025184,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
bool __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587280176,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:48",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
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
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/bpf/cpumask.c:bpf_cpumask_equal",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down",
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587280176,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
bool __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587568912,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:37",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_unbound_exclude_cpumask",
        "kernel/workqueue.c:wqattrs_equal",
        "kernel/workqueue.c:wqattrs_equal",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
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
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu",
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call",
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call",
        "kernel/bpf/cpumask.c:bpf_cpumask_equal",
        "drivers/xen/xen-acpi-processor.c:check_acpi_ids",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down",
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568912,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496097144,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496097144,
      "name": "__bitmap_equal",
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
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229423936,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229423936,
      "name": "__bitmap_equal",
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
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290341216,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290341216,
      "name": "__bitmap_equal",
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
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275165368,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275165368,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192192,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192192,
      "name": "__bitmap_equal",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127408,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/hv/channel_mgmt.c:init_vp_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127408,
      "name": "__bitmap_equal",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584175952,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175952,
      "name": "__bitmap_equal",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584280288,
      "name": "__bitmap_equal",
      "external": true,
      "loc": "lib/bitmap.c:46",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/time/tick-common.c:tick_check_preferred",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280288,
      "name": "__bitmap_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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

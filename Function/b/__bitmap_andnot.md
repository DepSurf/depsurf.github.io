# Function: <code>__bitmap_andnot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010624,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:191",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/cpuset.c:generate_sched_domains",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010624,
      "name": "__bitmap_andnot",
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301120,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:193",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301120,
      "name": "__bitmap_andnot",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420160,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:193",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420160,
      "name": "__bitmap_andnot",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441280,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:193",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441280,
      "name": "__bitmap_andnot",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621216,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:195",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621216,
      "name": "__bitmap_andnot",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837600,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:192",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837600,
      "name": "__bitmap_andnot",
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921232,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:189",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921232,
      "name": "__bitmap_andnot",
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584101040,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:189",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/sched/isolation.c:bitmap_andnot",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/net/phy/phy.c:phy_speed_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101040,
      "name": "__bitmap_andnot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223824,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "kernel/sched/isolation.c:bitmap_andnot",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223824,
      "name": "__bitmap_andnot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584629824,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:276",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584629824,
      "name": "__bitmap_andnot",
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584748880,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:276",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748880,
      "name": "__bitmap_andnot",
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777216,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:278",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777216,
      "name": "__bitmap_andnot",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207232,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:278",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207232,
      "name": "__bitmap_andnot",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042992,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:278",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042992,
      "name": "__bitmap_andnot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
bool __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025728,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:278",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025728,
      "name": "__bitmap_andnot",
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
bool __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587280720,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:278",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach_task",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "lib/group_cpus.c:group_cpus_evenly",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee",
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587280720,
      "name": "__bitmap_andnot",
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
bool __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587569456,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:267",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel",
        "kernel/workqueue.c:workqueue_unbound_exclude_cpumask",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/fair.c:should_we_balance",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:init_sched_groups_capacity",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_attach_task",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:partition_xcpus_del",
        "kernel/cgroup/cpuset.c:partition_xcpus_add",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "lib/group_cpus.c:group_cpus_evenly",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee",
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569456,
      "name": "__bitmap_andnot",
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496097552,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/fpsimd.c:sve_verify_vq_map",
        "arch/arm64/kernel/fpsimd.c:sve_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496097552,
      "name": "__bitmap_andnot",
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229424380,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229424380,
      "name": "__bitmap_andnot",
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290341840,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending",
        "arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/platforms/powernv/subcore.c:cpu_update_split_mode",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290341840,
      "name": "__bitmap_andnot",
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275165772,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275165772,
      "name": "__bitmap_andnot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192560,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/sched/isolation.c:bitmap_andnot",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192560,
      "name": "__bitmap_andnot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127776,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/sched/isolation.c:bitmap_andnot",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127776,
      "name": "__bitmap_andnot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584176320,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "kernel/sched/isolation.c:bitmap_andnot",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176320,
      "name": "__bitmap_andnot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __bitmap_andnot(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_andnot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584280656,
      "name": "__bitmap_andnot",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "kernel/sched/isolation.c:bitmap_andnot",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280656,
      "name": "__bitmap_andnot",
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

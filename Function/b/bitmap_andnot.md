# Function: <code>bitmap_andnot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579194264,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213144,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515254,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579566052,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580002278,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584410326,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_offline"
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
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579194881,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213827,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529372,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595257349,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:partition_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580034710,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584745670,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_offline"
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
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579124882,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206003,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225536,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553894,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602349,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:partition_sched_domains"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp"
      ]
    },
    {
      "addr": 18446744071580075923,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584935787,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:248",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566816,
      "name": "bitmap_andnot",
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
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579120701,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203631,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223855,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540193,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596421794,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579686714,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580080643,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020376,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_offline"
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
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579134632,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:257",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239500,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:257",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579567768,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:257",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746449,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:257",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071579866587,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:257",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585443484,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:257",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746449,
      "name": "bitmap_andnot.constprop.4",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579144185,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:288",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252028,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:288",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579595994,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:288",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579780817,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:288",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071579897197,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:288",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900721,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:288",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585686700,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:288",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780817,
      "name": "bitmap_andnot.constprop.4",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579209691,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275836,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823697,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071579944229,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948221,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580254970,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585816908,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823697,
      "name": "bitmap_andnot.constprop.5",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223438,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290240,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851905,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071579983066,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579986886,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580307085,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586050450,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586796684,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851905,
      "name": "bitmap_andnot",
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
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579225736,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296288,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465609,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900433,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071580033233,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580037014,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580355949,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586198498,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900433,
      "name": "bitmap_andnot",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579249815,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:309",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326624,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:309",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579486404,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:309",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579804525,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:309",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943585,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:309",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071580083652,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:309",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580087759,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:309",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580428661,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:309",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586961170,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:309",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:309",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943585,
      "name": "bitmap_andnot.isra.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579242791,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328222,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795237,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591290897,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071580066228,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580071167,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416167,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587046530,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591290897,
      "name": "bitmap_andnot.isra.0",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579244119,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330912,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579810975,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591233977,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071580066868,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580071882,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580417767,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586930338,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:307",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591233977,
      "name": "bitmap_andnot.isra.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284279,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386105,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579835324,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908192,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592121281,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071580200358,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580205683,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582183,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587492802,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:313",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592121281,
      "name": "bitmap_andnot.isra.0",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579338198,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451873,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948282,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022577,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617107620,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580353559,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580359634,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580783153,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588816008,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591492167,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579406965,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539481,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580107723,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580174586,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627771785,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580575885,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582518,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067243,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583264141,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590314717,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593271891,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:346",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579419013,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552308,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619517783,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580168971,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580241434,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619533385,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580655430,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157595,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cgroup/cpuset.c:update_tasks_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583484493,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588180664,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590634557,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591651376,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593727923,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:344",
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
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579451125,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579580084,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621814727,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580087970,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_unbound_exclude_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215259,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580299666,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:should_we_balance",
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:select_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621832327,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:init_sched_groups_capacity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580720646,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263099,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/cgroup/cpuset.c:update_tasks_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677341,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588471540,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590994125,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592392624,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594508083,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:321",
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
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490187588,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:sve_verify_vq_map",
        "arch/arm64/kernel/fpsimd.c:sve_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510887036,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491238088,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491614848,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498998216,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499200840,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/arch_topology.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243374024,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3225250940,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225571796,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 3231565252,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 3231732484,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/arch_topology.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282389620,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/powerpc/kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282421248,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/powerpc/kernel/rtas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282833392,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282838072,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/powerpc/mm/slice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283012112,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/powerpc/platforms/powernv/subcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/subcore.c:cpu_update_split_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283230576,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/powerpc/platforms/pseries/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055302520576,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284138116,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284607424,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292156156,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294863928,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
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
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271360130,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/riscv/mm/cacheflush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/cacheflush.c:flush_icache_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270627432,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271768088,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272016996,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276371096,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224584,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292096,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872545,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071580001969,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005750,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580324749,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585958706,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872545,
      "name": "bitmap_andnot",
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
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579159512,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227571,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579807553,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071579940641,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944422,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580272017,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585807970,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807553,
      "name": "bitmap_andnot",
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
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579225656,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293296,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860705,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071579993505,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997286,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580315997,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586148514,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860705,
      "name": "bitmap_andnot",
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
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579231064,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302128,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579470937,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906081,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446744071580040241,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044134,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580370750,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586257218,
      "name": "bitmap_andnot",
      "external": false,
      "loc": "include/linux/bitmap.h:293",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906081,
      "name": "bitmap_andnot",
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
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
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
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bitmap_andnot(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
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

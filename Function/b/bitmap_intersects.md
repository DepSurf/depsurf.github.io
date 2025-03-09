# Function: <code>bitmap_intersects</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579193476,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535166,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:task_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578995,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579637491,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746386,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769824,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580002803,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459334,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580819366,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:264",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579195110,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579546339,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590996,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579652515,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579768638,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793024,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047125,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580537056,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_cpu_callback",
        "kernel/padata.c:padata_cpu_callback",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944790,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586745336,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:ethtool_get_settings"
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
int bitmap_intersects(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579206710,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579595945,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071579651119,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677135,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795628,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579821042,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826637,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580086532,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580597782,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581017002,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586931880,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:277",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:ethtool_get_settings"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565680,
      "name": "bitmap_intersects",
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579204374,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579580255,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579597516,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579655042,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678667,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793346,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579819067,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826583,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580092292,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580627574,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581062970,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587057930,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:274",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:ethtool_get_settings"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579609551,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579627157,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685522,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579709301,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827010,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854459,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862398,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580145332,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580708550,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581174058,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587558853,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:292",
      "file": "net/core/ethtool.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579639340,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579660966,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717972,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749867,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860894,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888027,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579895725,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580205013,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580840213,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581318729,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863740,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:ethtool_get_settings"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579204006,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227165,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677020,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579695523,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579757444,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579789899,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579907856,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579935083,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579942758,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580257317,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580909157,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581402889,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588005637,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579216905,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240349,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579708935,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725548,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786192,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579817276,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943226,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579973722,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981563,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580308229,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581007077,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581515783,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589950327,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588319286,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:324",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579219193,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242573,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579751063,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579768012,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579832320,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579858856,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579993450,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580023242,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580031227,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580357109,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581061893,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581580247,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590177881,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588525942,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_intersects(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579240569,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266285,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786837,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579808700,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579874176,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579901608,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580040794,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
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
      "addr": 18446744071580073738,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580082306,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:get_nodes_in_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580430085,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581242565,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_validate_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581792215,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591196042,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589861078,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895504,
      "name": "bitmap_intersects",
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
int bitmap_intersects(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579232953,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258674,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579777957,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799979,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579868499,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896477,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580023994,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
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
      "addr": 18446744071580055850,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064882,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:get_nodes_in_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580417653,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284950,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_validate_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581840039,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591690934,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589900998,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890208,
      "name": "bitmap_intersects",
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
int bitmap_intersects(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579235033,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260242,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786101,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579807179,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579876435,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905003,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580024682,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
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
      "addr": 18446744071580056266,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065696,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580420437,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302902,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_validate_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870871,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591633961,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589807974,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:362",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898896,
      "name": "bitmap_intersects",
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
int bitmap_intersects(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579274336,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301446,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880546,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579904732,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579988008,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022676,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sd_init",
        "kernel/sched/topology.c:sd_init"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580157059,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
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
      "addr": 18446744071580188730,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199166,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580583749,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547494,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_validate_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582162617,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_in_oom_domain",
        "mm/mempolicy.c:policy_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592807973,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590570422,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:368",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014128,
      "name": "bitmap_intersects",
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
bool bitmap_intersects(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579327944,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356861,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579829398,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:unbind_workers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997632,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580016808,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093052,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580194781,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sd_init"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580302765,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
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
      "addr": 18446744071580339151,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580350198,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "kernel/irq/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580352220,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580784853,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581899670,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_validate_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582618401,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_in_oom_domain",
        "mm/mempolicy.c:policy_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594709051,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592187830,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:387",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593880403,
      "name": "bitmap_intersects",
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579393576,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427394,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579966806,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:unbind_workers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580159648,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185474,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270165,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627771811,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580515021,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
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
      "addr": 18446744071580556484,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580568523,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "kernel/irq/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574524,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068661,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333414,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_validate_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142289,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_in_oom_domain",
        "mm/mempolicy.c:policy_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596452949,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:401",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579405000,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439346,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014795,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:unbind_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580250642,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580336789,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619533411,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587917,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
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
      "addr": 18446744071580629348,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580642042,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "kernel/irq/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159077,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_fork",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374437,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582534630,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_validate_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583352433,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_in_oom_domain",
        "mm/mempolicy.c:policy_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596994277,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588179310,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591649634,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:399",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv",
        "drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579433896,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468978,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621819087,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:restrict_unbound_cpumask",
        "kernel/workqueue.c:unbind_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580296805,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390965,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621832353,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580652269,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
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
      "addr": 18446744071580694500,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580707276,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "kernel/irq/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264581,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_fork",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:tasks_nocpu_error",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758242,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541765,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582703606,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_validate_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583586545,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_in_oom_domain",
        "mm/mempolicy.c:policy_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597923669,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588470158,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592390882,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:376",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv",
        "drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490187476,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:sve_verify_vq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490929564,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490949240,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491020160,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491055848,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491183564,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491226552,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491236260,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491616356,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492423292,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_cpu_online",
        "kernel/padata.c:padata_cpu_online",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493017940,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503920684,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496394812,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502056864,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224463356,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/arm/kernel/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs",
        "arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 3224949252,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 3224963244,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3225027980,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 3225060736,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 3225206628,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3225241432,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3225249464,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225573020,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 3226307404,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_cpu_online",
        "kernel/padata.c:padata_cpu_online",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 3229725284,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3234808200,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282981148,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/powerpc/platforms/powernv/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283080572,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/powerpc/platforms/powernv/opal-imc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283782928,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283802120,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283897016,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283933708,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284085672,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284128432,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284136000,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284609020,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285694576,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_cpu_online",
        "kernel/padata.c:padata_cpu_online",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286445412,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297815680,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295508012,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271566210,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271575276,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271625546,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271650024,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271731278,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271761660,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271767046,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272018018,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272510060,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278337464,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579218041,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579241421,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579726983,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579743868,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579804672,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831208,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579962186,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991978,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579999963,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580325909,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030741,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581548983,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589780169,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588132678,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579152905,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177005,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579655591,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674252,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739184,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765784,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579900026,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579930650,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938635,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580273173,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580976821,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581490631,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589502992,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587845510,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579219113,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242493,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579713767,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579728380,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792688,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579819224,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579953722,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579983514,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991499,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580317157,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581021941,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581540295,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590223577,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588464502,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
  "name": "bitmap_intersects",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579224425,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248061,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579758695,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776156,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579838032,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:set_cpus_allowed_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579864344,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580000104,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580030154,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580038235,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580372069,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084885,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581605335,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590273935,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601414,
      "name": "bitmap_intersects",
      "external": false,
      "loc": "include/linux/bitmap.h:348",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int bitmap_intersects(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int bitmap_intersects(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bitmap_intersects(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
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
bool bitmap_intersects(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
</ul>

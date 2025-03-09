# Function: <code>__bitmap_intersects</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010736,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:207",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:guarantee_online_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010736,
      "name": "__bitmap_intersects",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301232,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_cpu_callback",
        "kernel/padata.c:padata_cpu_callback",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301232,
      "name": "__bitmap_intersects",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420272,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420272,
      "name": "__bitmap_intersects",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441408,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:209",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_set_affinity",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441408,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621344,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:211",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621344,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837712,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:208",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837712,
      "name": "__bitmap_intersects",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921344,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:205",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921344,
      "name": "__bitmap_intersects",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584101152,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:205",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101152,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223936,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:225",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223936,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630000,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:304",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:get_nodes_in_cpumask",
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/padata.c:padata_validate_cpumask",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630000,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584749056,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:304",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:get_nodes_in_cpumask",
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/padata.c:padata_validate_cpumask",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584749056,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777392,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:306",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/padata.c:padata_validate_cpumask",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777392,
      "name": "__bitmap_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207408,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:306",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sd_init",
        "kernel/sched/topology.c:sd_init",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/padata.c:padata_validate_cpumask",
        "mm/mempolicy.c:mempolicy_in_oom_domain",
        "mm/mempolicy.c:policy_nodemask",
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207408,
      "name": "__bitmap_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
bool __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043216,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:306",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/workqueue.c:unbind_workers",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/padata.c:padata_validate_cpumask",
        "mm/mempolicy.c:mempolicy_in_oom_domain",
        "mm/mempolicy.c:policy_nodemask",
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043216,
      "name": "__bitmap_intersects",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025984,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:306",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/workqueue.c:unbind_workers",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/padata.c:padata_validate_cpumask",
        "mm/mempolicy.c:mempolicy_in_oom_domain",
        "mm/mempolicy.c:policy_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025984,
      "name": "__bitmap_intersects",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587280976,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:306",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/workqueue.c:unbind_worker",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/bpf/cpumask.c:bpf_cpumask_intersects",
        "kernel/padata.c:padata_validate_cpumask",
        "mm/mempolicy.c:mempolicy_in_oom_domain",
        "mm/mempolicy.c:policy_nodemask",
        "lib/group_cpus.c:__group_cpus_evenly",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv",
        "drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587280976,
      "name": "__bitmap_intersects",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587569712,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:295",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/workqueue.c:restrict_unbound_cpumask",
        "kernel/workqueue.c:unbind_worker",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
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
        "kernel/cgroup/cpuset.c:guarantee_online_cpus",
        "kernel/trace/trace_events_filter.c:filter_pred_fn_call",
        "kernel/bpf/cpumask.c:bpf_cpumask_intersects",
        "kernel/padata.c:padata_validate_cpumask",
        "mm/mempolicy.c:mempolicy_in_oom_domain",
        "mm/mempolicy.c:policy_nodemask",
        "lib/group_cpus.c:__group_cpus_evenly",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv",
        "drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569712,
      "name": "__bitmap_intersects",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496097672,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:225",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/fpsimd.c:sve_verify_vq_map",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/padata.c:padata_cpu_online",
        "kernel/padata.c:padata_cpu_online",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "mm/sparse.c:sparse_add_section",
        "drivers/irqchip/irq-gic-v3-its.c:its_set_affinity",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496097672,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229424512,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:225",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229424512,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290342000,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:225",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "kernel/padata.c:padata_cpu_online",
        "kernel/padata.c:padata_cpu_online",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290342000,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275165908,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:225",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275165908,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192672,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:225",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192672,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127888,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:225",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127888,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584176432,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:225",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176432,
      "name": "__bitmap_intersects",
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
int __bitmap_intersects(const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_intersects",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584280768,
      "name": "__bitmap_intersects",
      "external": true,
      "loc": "lib/bitmap.c:225",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked",
        "kernel/sched/core.c:task_can_attach",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/fair.c:find_idlest_cpu",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects",
        "kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:validate_change",
        "kernel/cgroup/cpuset.c:guarantee_online_mems",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280768,
      "name": "__bitmap_intersects",
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

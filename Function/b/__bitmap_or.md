# Function: <code>__bitmap_or</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010528,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:169",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010528,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301024,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301024,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420064,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420064,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441152,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:171",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domain",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441152,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621088,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:173",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621088,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837504,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:170",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837504,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921136,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:167",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921136,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584100944,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:167",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:sched_domain_debug_one",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584100944,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223728,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:187",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223728,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584629728,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:254",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584629728,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584748784,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:254",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748784,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777120,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:256",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777120,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207136,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:256",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "mm/migrate.c:__set_migration_target_nodes",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207136,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042864,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:256",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "mm/migrate.c:__set_migration_target_nodes",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042864,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025568,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:256",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:nodelist_show",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025568,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587280560,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:256",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/bpf/cpumask.c:bpf_cpumask_or",
        "mm/rmap.c:set_tlb_ubc_flush_pending",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:nodelist_show",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "lib/group_cpus.c:__group_cpus_evenly",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587280560,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587569296,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:245",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one",
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:partition_xcpus_del",
        "kernel/cgroup/cpuset.c:partition_xcpus_add",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/bpf/cpumask.c:bpf_cpumask_or",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:nodelist_show",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "lib/group_cpus.c:__group_cpus_evenly",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569296,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496097440,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:187",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/fpsimd.c:sve_update_vq_map",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/sparse.c:sparse_add_section",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496097440,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229424252,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:187",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229424252,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290341616,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:187",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/slice.c:slice_is_hugepage_only_range",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290341616,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275165656,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:187",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275165656,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192464,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:187",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192464,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127680,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:187",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127680,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584176224,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:187",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176224,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void __bitmap_or(long unsigned int * dst, const long unsigned int * bitmap1, const long unsigned int * bitmap2, unsigned int bits)
```

```json
{
  "name": "__bitmap_or",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584280560,
      "name": "__bitmap_or",
      "external": true,
      "loc": "lib/bitmap.c:187",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "mm/rmap.c:try_to_unmap_one",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/net/phy/sfp-bus.c:sfp_parse_support",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280560,
      "name": "__bitmap_or",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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

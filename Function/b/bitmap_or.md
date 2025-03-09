# Function: <code>bitmap_or</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579194237,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407044,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535194,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579881354,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003103,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580726352,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580814183,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583129161,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585872915,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579194854,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419121,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595256676,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579913111,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580038523,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580845530,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939551,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583423625,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586274366,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579125461,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205988,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439441,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595501285,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943637,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580070504,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915947,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581007074,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_rebind_nodemask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583549331,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586478547,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:230",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579122054,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:229",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203616,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:229",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427578,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:229",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683803,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:229",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domain",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949041,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:229",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580075400,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:229",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959947,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:229",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587011,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:229",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586603053,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:229",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579136150,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579455820,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714136,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579864938,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579994753,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580128184,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581061865,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833055,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086329,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579145798,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:270",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579470269,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:270",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579750195,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:270",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899089,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:270",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580046849,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:270",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580189832,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:270",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200778,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:270",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584033570,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:270",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586425907,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:270",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587384489,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:270",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579211433,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227123,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503984,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579790227,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943481,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579946475,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580093681,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580237736,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284349,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584116306,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586547499,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586571133,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587564601,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579225181,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240307,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579523064,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818057,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579982270,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579985100,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580137552,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580288248,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358649,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589950335,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584305254,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586796760,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586822666,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587840377,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:271",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579227453,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242531,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579549144,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579866090,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032462,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580035228,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580185696,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580336584,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418328,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590177889,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584439926,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586968762,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045209,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
void bitmap_or(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579241474,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266243,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579576368,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579903372,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580083097,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580085996,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580251600,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580410104,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619702,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591196050,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585003493,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587792342,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587886759,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588905497,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589896515,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:291",
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
      "addr": 18446744071579895056,
      "name": "bitmap_or",
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
void bitmap_or(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579234954,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258628,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271298,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557984,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898284,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580065673,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580069580,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580235424,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397416,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665869,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591690942,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585124229,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587850358,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587948296,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588918073,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589935565,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
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
      "addr": 18446744071579889760,
      "name": "bitmap_or",
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
void bitmap_or(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579244964,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260196,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272690,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562833,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905711,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580066299,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580070240,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580239908,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580403688,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688122,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591633969,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585004814,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587730528,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587834400,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588806687,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589843949,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:289",
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
      "addr": 18446744071579898880,
      "name": "bitmap_or",
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
void bitmap_or(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579285141,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301404,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315592,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579638506,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580023437,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580199769,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580203840,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580390004,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580566392,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581957300,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592807981,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245531,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__set_migration_target_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585446252,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588324032,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588427978,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589499327,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590606301,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:295",
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
      "addr": 18446744071580014080,
      "name": "bitmap_or",
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
void bitmap_or(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579339181,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356819,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579373494,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734713,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580195531,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580352924,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580357856,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580609487,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580761639,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374638,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594709059,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716094,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__set_migration_target_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586587756,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589714402,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589827218,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590982172,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592226836,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:314",
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
      "addr": 18446744071593880380,
      "name": "bitmap_or",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579396637,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427352,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434294,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579861269,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580386026,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580575220,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580580608,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580872065,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039591,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582878066,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596452961,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583263768,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:nodelist_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587828578,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591331284,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592687759,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594058516,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:328",
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579420048,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439304,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446348,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911441,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580454802,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580653536,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580957404,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127687,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374261,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_or"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583083891,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:set_tlb_ubc_flush_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596994289,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583484120,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:nodelist_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588099698,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588180002,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692661,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593118751,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594436980,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:326",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579445360,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468936,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579476108,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950689,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580514437,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718752,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621851648,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048988,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226711,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:partition_xcpus_del",
        "kernel/cgroup/cpuset.c:partition_xcpus_add",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541589,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_or"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583265955,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597923682,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583676968,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memory-tiers.c:nodelist_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588435794,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588470850,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:__group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592435687,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593871583,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595239351,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:303",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490187344,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:sve_update_vq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490268072,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/arm64/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/alternative.c:__apply_alternatives"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490697916,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491058872,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491237376,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491410944,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491602084,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503920704,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496326936,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499960048,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501314032,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224463244,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/arm/kernel/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs",
        "arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 3224766072,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3225063724,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 3225249664,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225406804,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 3225569932,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 3229660492,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3232499000,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 3233800832,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282387832,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/powerpc/kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282833688,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282840512,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/powerpc/mm/slice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/slice.c:slice_is_hugepage_only_range",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283525608,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283937040,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284137476,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284358452,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284584516,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297815700,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290645156,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293285488,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294847616,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271424178,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271653098,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271767224,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272011940,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275377596,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277039140,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579226301,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579241379,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579522808,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579838442,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580001198,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003964,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580154496,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580305384,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387176,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589780177,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584408662,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586725770,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670201,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579161229,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176963,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451608,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579773018,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579939870,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579942636,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604735647,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100608,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580252722,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329918,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589503000,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343862,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586592986,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587444073,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579227373,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242451,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579522728,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826458,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579992734,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579995500,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580145968,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580296632,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378376,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590223585,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584391574,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586923322,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001353,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
  "name": "bitmap_or",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579232781,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248019,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555688,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871594,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039470,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580042236,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580197952,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580351288,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581441773,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590273943,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497638,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587029770,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_parse_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588116793,
      "name": "bitmap_or",
      "external": false,
      "loc": "include/linux/bitmap.h:275",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void bitmap_or(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void bitmap_or(long unsigned int * dst, const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
</ul>

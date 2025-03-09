# Function: <code>bitmap_parselist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bitmap_parselist(const char * bp, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583013712,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:583",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:isolated_cpu_setup",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583013712,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bitmap_parselist(const char * bp, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583304608,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:585",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583304608,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bitmap_parselist(const char * bp, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583423936,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:627",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583423936,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bitmap_parselist(const char * bp, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444256,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:627",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444256,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bitmap_parselist(const char * bp, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583624240,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:623",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624240,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bitmap_parselist(const char * bp, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840768,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:620",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840768,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bitmap_parselist(const char * bp, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583923920,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:615",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583923920,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103216,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:622",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103216,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226000,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:642",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226000,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584633136,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:638",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633136,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584752176,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:638",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584752176,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780112,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:650",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780112,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585211136,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:780",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211136,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586046992,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:796",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046992,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587030800,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:807",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030800,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587285952,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:807",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/taskstats.c:parse",
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587285952,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 963
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587633168,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap-str.c:374",
      "file": "lib/bitmap-str.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:workqueue_unbound_cpus_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/rcu/tree.c:rcu_nocb_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/taskstats.c:parse",
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap-str.c:bitmap_parselist_user",
        "drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587633168,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 963
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496100096,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:642",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496100096,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229427112,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:642",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229427112,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290345584,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:642",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290345584,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275168554,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:642",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275168554,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194736,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:642",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194736,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129952,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:642",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/rcu/tree.c:rcu_nocb_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129952,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584178496,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:642",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178496,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int bitmap_parselist(const char * buf, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parselist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282832,
      "name": "bitmap_parselist",
      "external": true,
      "loc": "lib/bitmap.c:642",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/taskstats.c:parse",
        "mm/mempolicy.c:mpol_parse_str",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/input/keyboard/atkbd.c:atkbd_set_force_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282832,
      "name": "bitmap_parselist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * bp</code>
</li>
</ul>
</details>
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

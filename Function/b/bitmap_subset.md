# Function: <code>bitmap_subset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579045273,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:273",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:fixup_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193734,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:273",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579482897,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:273",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535387,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:273",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:build_sched_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579881381,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:273",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006262,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:273",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580148874,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:273",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:273",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580817334,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:273",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SyS_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585560858,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:273",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler"
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579041732,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194329,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496755,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572186,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910891,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580042569,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580183258,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580571875,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580949930,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:SyS_migrate_pages",
        "mm/mempolicy.c:SyS_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585954595,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler"
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
int bitmap_subset(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579041665,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:fixup_irqs",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206078,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517004,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579597444,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": [
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    },
    {
      "addr": 18446744071579941653,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580079906,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580223962,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580638592,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581022418,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586142995,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:286",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566704,
      "name": "bitmap_subset",
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579034291,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203705,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504659,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579577647,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635068,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579681720,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949906,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580085445,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580233690,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580670231,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581068265,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586231898,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:283",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler",
        "drivers/input/input.c:input_attach_handler"
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579531391,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:301",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579607343,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:301",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664667,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:301",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711107,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:301",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579995601,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:301",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580138341,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:301",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580284922,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:301",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580755287,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:301",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581179401,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:301",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586696180,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:301",
      "file": "drivers/input/input.c",
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579559044,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579637455,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697985,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579743080,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047697,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580200007,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580346181,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580890263,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581324281,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586962581,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:332",
      "file": "drivers/input/input.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579222653,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579596260,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675135,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579736945,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579783025,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580094529,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580256042,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580402197,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580963994,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581408428,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587123445,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/input/input.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579235859,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579617676,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579707067,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579766985,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579811619,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580138398,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580306952,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580455077,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058119,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581520619,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585989462,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587388258,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/input/input.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579238051,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275374,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645660,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749163,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579809631,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579859702,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580186542,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580355816,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580504037,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113879,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581585178,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586136438,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587590290,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/input/input.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int bitmap_subset(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579261299,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301826,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676499,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579785052,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579848850,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579901803,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
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
      "addr": 18446744071580077054,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:hk_should_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580251326,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580428585,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580590245,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292334,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581797114,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586891878,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588448306,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:373",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895520,
      "name": "bitmap_subset",
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
int bitmap_subset(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579253795,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307234,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:activate_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656323,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579775845,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579840804,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579881859,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896676,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
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
      "addr": 18446744071580059182,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:hk_should_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580235150,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416091,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580579419,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336494,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581845018,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586976881,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588478306,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890224,
      "name": "bitmap_subset",
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
int bitmap_subset(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579255491,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309435,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579662757,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784449,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579849841,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890994,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905196,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580060223,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580240462,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580417691,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580581947,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356190,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875821,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859473,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588360418,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:371",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898912,
      "name": "bitmap_subset",
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
int bitmap_subset(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579296435,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358059,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739921,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579878414,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579954790,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005752,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022866,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580192799,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391092,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582883,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580753403,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604046,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582167389,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587422689,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589023618,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:377",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014144,
      "name": "bitmap_subset",
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
bool bitmap_subset(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579351811,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421238,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579844307,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994529,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580069564,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580136280,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580194897,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580343202,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580609143,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580783898,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/cgroup/cpuset.c:is_cpuset_subset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968487,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964174,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582624720,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588736433,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590462254,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:397",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593880424,
      "name": "bitmap_subset",
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579422496,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504694,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579984157,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580156125,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580240653,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580310800,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580385790,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580560850,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580873696,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067530,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/cgroup/cpuset.c:is_cpuset_subset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264439,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582397294,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583149120,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590221793,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592104862,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434275,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579516966,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580036797,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218357,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580306570,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580341245,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580454565,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634322,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580956992,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157882,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/cgroup/cpuset.c:is_cpuset_subset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359591,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374485,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_subset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582603198,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583359392,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590541665,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592528606,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579463859,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545686,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580077508,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580267157,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580358682,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580392286,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580514202,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699474,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621851721,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048576,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263386,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:prstate_housekeeping_conflict",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:remote_cpus_update",
        "kernel/cgroup/cpuset.c:remote_partition_disable",
        "kernel/cgroup/cpuset.c:tasks_nocpu_error",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:is_cpuset_subset",
        "kernel/cgroup/cpuset.c:is_cpuset_subset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581465767,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541813,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_subset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774654,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583595840,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590897697,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593273198,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:386",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id",
        "drivers/input/input.c:input_match_device_id"
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490816416,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490927708,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490989840,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491056756,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491411816,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491614796,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491781920,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492481860,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493023172,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499201316,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:cpu_coregroup_mask",
        "drivers/base/arch_topology.c:cpu_coregroup_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500732936,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/input/input.c",
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224947236,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 3224999460,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 3225061600,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 3225407752,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 3225571776,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 3225729240,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 3231732808,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:cpu_coregroup_mask",
        "drivers/base/arch_topology.c:cpu_coregroup_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3233255444,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/input/input.c",
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282832704,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282927528,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/powerpc/sysdev/xics/xics-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xics/xics-common.c:xics_get_irq_server"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283187660,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/powerpc/platforms/pseries/hotplug-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283648968,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283780816,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283859428,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283934872,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284360124,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284607328,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284829164,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285767176,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286452016,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294180088,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/input/input.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271564396,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271601966,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271650794,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272016368,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272097518,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276492314,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:cpu_coregroup_mask",
        "drivers/base/arch_topology.c:cpu_coregroup_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277577222,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/input/input.c",
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
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579236899,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274078,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579621964,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725115,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579785407,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579832054,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155342,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580324616,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580472837,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082727,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581553914,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585896806,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587283106,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/input/input.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579172179,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209422,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579550332,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579653675,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716201,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579766630,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604735668,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580101454,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271884,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580419877,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029911,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581495562,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756582,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587051538,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/input/input.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579237971,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275278,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579619244,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711867,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769999,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579820070,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580146814,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580315864,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580464085,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581073927,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581545226,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586086454,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587541538,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/input/input.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_subset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579243443,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281170,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579652908,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579756818,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818062,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865190,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580198798,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580370617,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519749,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:add_del_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135655,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581610346,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586194742,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587652738,
      "name": "bitmap_subset",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "drivers/input/input.c",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int bitmap_subset(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int bitmap_subset(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bitmap_subset(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
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
bool bitmap_subset(const long unsigned int * src1, const long unsigned int * src2, unsigned int nbits)
```
</details>
</li>
</ul>

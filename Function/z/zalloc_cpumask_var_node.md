# Function: <code>zalloc_cpumask_var_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579194646,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:686",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595082599,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:686",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_workqueues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595091154,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:686",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595091237,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:686",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738418,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:686",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908041,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:686",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:hotplug_cfd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582797904,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:686",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595251429,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:686",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595310823,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:686",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579195318,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:688",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595249937,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:688",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_workqueues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595258775,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:688",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595258858,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:688",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760170,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:688",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579939989,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:688",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070688,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:688",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595432810,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:688",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595493779,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:688",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583348208,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:77",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348208,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588199600,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:109",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588199600,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588748432,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:126",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748432,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126208,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:127",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126208,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589360896,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:127",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360896,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817952,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817952,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590044512,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590044512,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585038464,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585038464,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585190368,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190368,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072768,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072768,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585519456,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519456,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586671792,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask",
        "kernel/workqueue.c:wq_numa_init",
        "kernel/sched/build_policy.c:init_sched_dl_class",
        "kernel/sched/build_policy.c:init_sched_rt_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_alloc_hctx",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671792,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627695014,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:824",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627760964,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:824",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627768743,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:824",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627769973,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:824",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627770777,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:824",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:init_sched_dl_class",
        "kernel/sched/build_policy.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580502932,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:824",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580916348,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:824",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586467866,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:824",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_hctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628045267,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:824",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628137605,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:824",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init"
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
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619452710,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:876",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619521796,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:876",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619529847,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:876",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619531319,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:876",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619532377,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:876",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:init_sched_dl_class",
        "kernel/sched/build_policy.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574484,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:876",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001996,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:876",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586713482,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:876",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_hctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619811347,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:876",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619904373,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:876",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init"
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
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621748822,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:894",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621821808,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:894",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621828696,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:894",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621830151,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:894",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621831337,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:894",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:init_sched_dl_class",
        "kernel/sched/build_policy.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580638771,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:894",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581098156,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:894",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586985964,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:894",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_hctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622119843,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:894",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622214405,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:894",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init"
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
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510877600,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510886092,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510886208,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491168960,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491457188,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495866064,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243373108,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 3243373200,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 3225195456,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 3225443252,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3229213220,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302416208,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302508348,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302519308,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302519484,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284068476,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284407772,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290065404,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270626542,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270626672,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271721712,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271912840,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274991638,
      "name": "zalloc_cpumask_var_node",
      "external": false,
      "loc": "include/linux/cpumask.h:773",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589646768,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646768,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372640,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372640,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590090144,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090144,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```

```json
{
  "name": "zalloc_cpumask_var_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590140400,
      "name": "zalloc_cpumask_var_node",
      "external": true,
      "loc": "lib/cpumask.c:128",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "kernel/workqueue.c:workqueue_init",
        "kernel/sched/rt.c:init_sched_rt_class",
        "kernel/sched/deadline.c:init_sched_dl_class",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140400,
      "name": "zalloc_cpumask_var_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```
</details>
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
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
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
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t * mask, gfp_t flags, int node)
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

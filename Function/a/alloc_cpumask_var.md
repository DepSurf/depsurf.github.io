# Function: <code>alloc_cpumask_var</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:669",
      "file": "net/core/net-sysfs.c",
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
  "name": "alloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:671",
      "file": "net/core/net-sysfs.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583348263,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:93",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:alloc_sched_domains",
        "kernel/sched/core.c:SyS_sched_getaffinity",
        "kernel/sched/core.c:SyS_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:compat_SyS_sched_getaffinity",
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:alloc_trial_cpuset",
        "kernel/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/flow.c:flow_cache_flush",
        "net/core/net-sysfs.c:store_xps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348240,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588199655,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:125",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:SyS_sched_getaffinity",
        "kernel/sched/core.c:SyS_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:compat_SyS_sched_getaffinity",
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/flow.c:flow_cache_flush",
        "net/core/net-sysfs.c:store_xps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588199632,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588748487,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:142",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/sched/core.c:SyS_sched_getaffinity",
        "kernel/sched/core.c:SyS_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:compat_SyS_sched_getaffinity",
        "kernel/compat.c:compat_SyS_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748464,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589126256,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:143",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126240,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589360944,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:143",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360928,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589818000,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/smp.c:native_send_call_func_ipi",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817984,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590044560,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590044544,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585038512,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585038496,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585190416,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190400,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585072816,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072800,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585519504,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:update_sched_domain_debugfs",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x64_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x64_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "fs/io-wq.c:io_wq_create",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519488,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586671856,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/build_utility.c:alloc_sched_domains",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "io_uring/io-wq.c:io_wq_create",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671824,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
  "name": "alloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579078422,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627544699,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627601629,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407694,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579416968,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427265,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627643258,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627663448,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579538863,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711591,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627753410,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627756725,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:alloc_frozen_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991451,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580157682,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627770151,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580290593,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580343434,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:membarrier_global_expedited",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:alloc_sched_domains",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:cpupri_init",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627780580,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580511774,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580556395,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580575455,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580752251,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786534,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627794533,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953282,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581064560,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265804,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329116,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375059,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627829117,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/trace/trace_boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627838444,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582336961,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586746036,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586871796,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587828415,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588177470,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588698460,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589160283,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589167022,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589412485,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590314678,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590429130,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590463604,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628123450,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592664488,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592687575,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592700825,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592710250,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592721763,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593239264,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593271769,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593580887,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:840",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "alloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579078214,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619290961,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619337653,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619355693,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409219,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429080,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439217,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619399734,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619420408,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553513,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579724871,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619513154,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619516549,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:alloc_frozen_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580045243,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206514,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619531635,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580358001,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580410448,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:membarrier_global_expedited",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:alloc_sched_domains",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619543460,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584156,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580629249,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834833,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580869718,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619557413,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040258,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581154928,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360965,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423804,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469666,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562419,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619593497,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/trace/trace_boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619602972,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582538489,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016081,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_register_iowq_aff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587137655,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588099535,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588180209,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:group_cpus_evenly",
        "lib/group_cpus.c:group_cpus_evenly",
        "lib/group_cpus.c:group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588453502,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588986556,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589453467,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589460402,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589711573,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590634518,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590748682,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590786532,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591742910,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619890098,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593095192,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593118567,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593131846,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593147146,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593158851,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593700294,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593727801,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594052519,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:892",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "alloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579103990,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621583519,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621630325,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621649709,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438172,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458664,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468849,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621694759,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621715384,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581193,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759735,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621810080,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621813461,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:alloc_frozen_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621819583,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_pod_type",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_unbound_exclude_cpumask",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580254834,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621830529,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580413569,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580482462,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__do_sys_membarrier",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:alloc_sched_domains",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621842372,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648508,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580694401,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621852110,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924257,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960214,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621858789,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581137474,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260480,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581467189,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532444,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576710,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create_systems",
        "kernel/trace/trace.c:trace_array_create_systems",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674627,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621897033,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/trace/trace_boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621906524,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582707640,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587410785,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "io_uring/register.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/register.c:io_register_iowq_aff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587423735,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588435631,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588471057,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:group_cpus_evenly",
        "lib/group_cpus.c:group_cpus_evenly",
        "lib/group_cpus.c:group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588750462,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589290635,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589761451,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589768402,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589993476,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/pmdomain/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pmdomain/core.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590047349,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590994086,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591129332,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:cpulist_read",
        "drivers/base/node.c:cpumap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592486494,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622199842,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593847975,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593871399,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593885125,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593900954,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593912659,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594478038,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594507961,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594842983,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:912",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:show_rps_map"
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
  "name": "alloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/pci/controller/pci-xgene-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/pci/controller/pcie-iproc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "net/core/net-sysfs.c",
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
  "name": "alloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "net/core/net-sysfs.c",
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
  "name": "alloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "arch/powerpc/kernel/rtas.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "arch/powerpc/platforms/powernv/subcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "arch/powerpc/platforms/pseries/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "net/core/net-sysfs.c",
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
  "name": "alloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:756",
      "file": "net/core/net-sysfs.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589646816,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646800,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589372688,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/hv/channel_mgmt.c:init_vp_index",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372672,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590090192,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090176,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "alloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590140448,
      "name": "alloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:144",
      "file": "lib/cpumask.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:zalloc_cpumask_var"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common",
        "kernel/cpu.c:alloc_frozen_cpus",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_setaffinity",
        "kernel/sched/core.c:__x64_sys_sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/topology.c:alloc_sched_domains",
        "kernel/sched/debug.c:register_sched_domain_sysctl",
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_setaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_setaffinity",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/padata.c:store_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/base/cpu.c:print_cpus_isolated",
        "drivers/base/cpu.c:print_cpus_offline",
        "drivers/base/node.c:node_read_cpumap",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140432,
      "name": "alloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
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
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
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
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool alloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
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

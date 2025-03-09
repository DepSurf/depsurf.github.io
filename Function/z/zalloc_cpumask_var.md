# Function: <code>zalloc_cpumask_var</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594987427,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595005488,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:init_amd_e400_c1e_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595011841,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595030464,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213368,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe",
        "arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo",
        "arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488630,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_unbound_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579524466,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:sched_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595091111,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648653,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579650223,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769577,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595100587,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
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
      "addr": 18446744071579910063,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580221918,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808133,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_init_tags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583129030,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583572370,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583750683,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583757130,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585864924,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585883887,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585892282,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585896333,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586407358,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:680",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_xps_map",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595150180,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595169055,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:init_amd_e400_c1e_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595176446,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595196076,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214042,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503134,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595258582,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595258744,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664253,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665757,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595261733,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792777,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595268629,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
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
      "addr": 18446744071579939775,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258730,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087232,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_init_tags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583423494,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894683,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076830,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584083126,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586266742,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586283949,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586293014,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586296205,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586850148,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:682",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_xps_map",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583348256,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:99",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus",
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus",
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:show_xps_map",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348256,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588199648,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:131",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:show_xps_map",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588199648,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588748480,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:148",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:SyS_membarrier",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748480,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126256,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:149",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126256,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589360944,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:149",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360944,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589818000,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589818000,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590044560,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590044560,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585038512,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:init_irq_default_affinity",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init_all_cpus",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585038512,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585190416,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:init_irq_default_affinity",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init_all_cpus",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190416,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072816,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072816,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585519504,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/time/hrtimer.c:clock_was_set",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519504,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586671856,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/build_policy.c:cpudl_init",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:membarrier_global_expedited",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:cpupri_init",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/irq/affinity.c:irq_build_affinity_masks",
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/time/hrtimer.c:clock_was_set",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/pci/pci-driver.c:pci_call_probe",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/dev.c:netif_get_num_default_rss_queues",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671856,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
  "name": "zalloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627601629,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407694,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427265,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627643258,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
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
      "addr": 18446744071579538863,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991451,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627770151,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580290593,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580343434,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:membarrier_global_expedited",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:init_rootdomain",
        "kernel/sched/build_utility.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627780580,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580556395,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786534,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627794533,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
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
      "addr": 18446744071581064560,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
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
      "addr": 18446744071581329116,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581403025,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627838444,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587828415,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588177470,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588698460,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589160283,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589167022,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590429130,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628123450,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592664514,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592700825,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592710250,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592721763,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593271769,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593570667,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "zalloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619337653,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619355693,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409219,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439217,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619399734,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
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
      "addr": 18446744071579553513,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580045243,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206514,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619531635,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580358001,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580410448,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:membarrier_global_expedited",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580629249,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580869718,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619557413,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581154928,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
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
      "addr": 18446744071581423804,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469848,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562419,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619602972,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588099535,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588180209,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588986556,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589453467,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589460402,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590748682,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591742910,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619890098,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593095218,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593131846,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593147146,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593158851,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593727801,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594042651,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:898",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "zalloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621630325,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621649709,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438172,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468849,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621694759,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
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
      "addr": 18446744071579581193,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621819583,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_pod_type",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_unbound_exclude_cpumask",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580254834,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621830529,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580413569,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580482462,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__do_sys_membarrier",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
        "kernel/sched/build_utility.c:sched_init_domains",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580694401,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_nohz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924257,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960214,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621858789,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260480,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
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
      "addr": 18446744071581532444,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576906,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create_systems",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674627,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621906524,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588435631,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588471057,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
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
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589290635,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589761451,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589768402,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589993476,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/pmdomain/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pmdomain/core.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592486494,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622199842,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593848001,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593885125,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593900954,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593912659,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594507961,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594832939,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:918",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "zalloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490380000,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_init",
        "virt/kvm/kvm_main.c:kvm_make_all_cpus_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490824400,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510886024,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491049028,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491051160,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491061796,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491098728,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:__arm64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491227016,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491237848,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510902536,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
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
      "addr": 18446603336491456440,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491613960,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
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
      "addr": 18446603336491835696,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491886104,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510935616,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_all_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496326764,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497428040,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497642008,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497663164,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499101568,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501302968,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502262124,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225054716,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225056564,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225057444,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225250820,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3243389420,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
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
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243399228,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 3225777640,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3225828612,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3243425076,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3229660380,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3231654996,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3233791224,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
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
  "name": "zalloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282943028,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "arch/powerpc/sysdev/xive/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283187516,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "arch/powerpc/platforms/pseries/hotplug-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283659220,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302519200,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283925732,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283927916,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283940712,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283987056,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284128808,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284137764,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
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
      "addr": 13835058055302538604,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
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
      "addr": 13835058055284407340,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284605836,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
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
      "addr": 13835058055284905012,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284966548,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302581428,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290644956,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292287744,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294834228,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295756804,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271645336,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271646988,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271647252,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271767964,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272004668,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272137786,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272176030,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276421368,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "zalloc_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:767",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589646816,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646816,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372688,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372688,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590090192,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090192,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```

```json
{
  "name": "zalloc_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590140448,
      "name": "zalloc_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:150",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/cpupri.c:cpupri_init",
        "kernel/sched/cpudeadline.c:cpudl_init",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/events/core.c:perf_event_init",
        "lib/cpu_rmap.c:cpu_rmap_update",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/base/power/domain.c:pm_genpd_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/speedstep-centrino.c:centrino_target",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140448,
      "name": "zalloc_cpumask_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
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
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t * mask, gfp_t flags)
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

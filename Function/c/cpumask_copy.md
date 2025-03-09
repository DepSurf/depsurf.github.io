# Function: <code>cpumask_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578978111,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578993213,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594987522,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579044998,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174963,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595030371,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191814,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194339,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210322,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211474,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212906,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215042,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322286,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377621,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_present",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465227,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515428,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545578,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579619988,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738691,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579743685,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769629,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:irq_affinity_hint_proc_show",
        "kernel/irq/proc.c:default_affinity_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803832,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579883484,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580004033,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:alloc_trial_cpuset",
        "kernel/cpuset.c:alloc_trial_cpuset",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_bind",
        "kernel/cpuset.c:cpuset_bind",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_init_smp",
        "kernel/cpuset.c:cpuset_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595110686,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197207,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580204108,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:trace_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580460248,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:__padata_set_cpumasks",
        "kernel/padata.c:__padata_set_cpumasks",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595132196,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:setup_vmstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582800016,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582964631,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace",
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583750551,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583758089,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583858129,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585864401,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585884023,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585891958,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578978093,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989837,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595150272,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579041074,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175488,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595195995,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192219,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194966,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211467,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212091,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213626,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215979,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327876,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390133,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595250295,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529543,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579574049,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634212,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761140,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765845,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793058,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799298,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831816,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579913036,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595275740,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_init_smp",
        "kernel/cpuset.c:cpuset_init_smp",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_bind",
        "kernel/cpuset.c:cpuset_bind",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:alloc_trial_cpuset",
        "kernel/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595280062,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580232616,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595283455,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580537168,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583073545,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251878,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076692,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084039,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188481,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586265824,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586284092,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586292617,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
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
void cpumask_copy(struct cpumask * dstp, const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578980128,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991711,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595393039,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040998,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125150,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185926,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595438769,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203941,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206574,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223136,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223760,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225313,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227504,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343164,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410485,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518361,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553997,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599586,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579658778,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579787988,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579791988,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579821075,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826548,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
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
      "addr": 18446744071579862722,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943574,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595522204,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_init_smp",
        "kernel/cpuset.c:cpuset_init_smp",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_bind",
        "kernel/cpuset.c:cpuset_bind",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_css_online",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:alloc_trial_cpuset",
        "kernel/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595526562,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595530071,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580601074,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583187589,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_queue_reinit_prepare",
        "block/blk-mq.c:blk_mq_queue_reinit_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367238,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218421,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ]
    },
    {
      "addr": 18446744071584226352,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584241405,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584370001,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586469902,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586488279,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586496820,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:514",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584218421,
      "name": "cpumask_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578964126,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578984469,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596312234,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033824,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121077,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184817,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596359481,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201137,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201765,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204235,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220832,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221504,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223633,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225200,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337180,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398437,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506361,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540383,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579577670,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683788,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579785508,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579791668,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579819100,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826390,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
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
      "addr": 18446744071579870950,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948978,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596441311,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596445972,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596450125,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580628424,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584292139,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584298750,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584317821,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584452881,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586594607,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612740,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586620615,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588216291,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:542",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578967406,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602629803,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134989,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200468,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602677442,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218876,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239296,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362616,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426453,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533081,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579567990,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579607366,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712796,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730893,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579817940,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825172,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854492,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862214,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
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
      "addr": 18446744071579914342,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994690,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602767280,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602772025,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602776092,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580709432,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690256,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584697816,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584717106,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584863489,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587077919,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587095796,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587103609,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766243,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:546",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578970135,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602798422,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579025457,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579144740,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212356,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602848905,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230965,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251841,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290117,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375016,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579440933,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579560659,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579596179,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579637531,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579744239,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760709,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851684,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579858915,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888060,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897026,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579958787,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580046796,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602941169,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602946018,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602950149,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580844034,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584916509,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584924145,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584944530,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585094567,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375664,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587394021,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587401664,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589144995,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:548",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578968262,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604592502,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029547,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579210277,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236036,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604645710,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254661,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275640,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314329,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402680,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474437,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579597875,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675211,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784170,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803589,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898676,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906162,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579935116,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943987,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003683,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093628,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604739108,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604743908,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604748063,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910050,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020413,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585028049,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048514,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585176734,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205351,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587555600,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587573989,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587582032,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774235,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589380131,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578975213,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604688147,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037201,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224005,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249494,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604743435,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268678,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290057,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329481,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418118,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579492309,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579609070,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579707182,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579812783,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831667,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579933493,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579940614,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579973755,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579982552,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580046407,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137499,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604840806,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604845617,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604849299,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009220,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585224083,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231804,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585252676,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585389183,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585417536,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585989640,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587830827,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587849907,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587855497,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588079149,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589837181,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:560",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578977613,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700579,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039521,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226315,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604756830,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271046,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296105,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333593,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421302,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579472975,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518245,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647134,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749278,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860575,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579879971,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579983621,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990534,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580023275,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032744,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580095495,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185643,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604874824,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604879635,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604883410,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581064300,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585360515,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585368348,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585390564,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585529695,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585558256,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586136616,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588035658,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054723,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588059850,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588284957,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590063325,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578987440,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609048823,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048849,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579244033,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609103213,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299984,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326441,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363113,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450526,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495199,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547637,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579679252,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784984,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899187,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:init_overlap_sched_group",
        "kernel/sched/topology.c:build_group_from_child_sched_domain",
        "kernel/sched/topology.c:build_group_from_child_sched_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579922844,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580011395,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580031925,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:desc_set_defaults"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580038335,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580073771,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580084000,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580159767,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580251550,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609202707,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609207362,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580675966,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244815,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:__padata_set_cpumasks",
        "kernel/padata.c:__padata_set_cpumasks",
        "kernel/padata.c:__padata_set_cpumasks",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585060221,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586069643,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586076280,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586100015,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586246991,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586278656,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586892056,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588896907,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588915985,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588924234,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589165601,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:597",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578988928,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612112167,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052145,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579236881,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612168129,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305502,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328044,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362137,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447790,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477631,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529333,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659380,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579777565,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579893907,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:init_overlap_sched_group",
        "kernel/sched/topology.c:build_group_from_child_sched_domain",
        "kernel/sched/topology.c:build_group_from_child_sched_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579916716,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579989789,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580015637,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:desc_set_defaults"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580021519,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580055883,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580066576,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580144199,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580235374,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612269293,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612273953,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580666886,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581287510,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:__padata_set_cpumasks",
        "kernel/padata.c:__padata_set_cpumasks",
        "kernel/padata.c:__padata_set_cpumasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585209661,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586191642,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586197720,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586365215,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586398752,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586977036,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588909467,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588928098,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588936666,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589161835,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:603",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578997904,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614251981,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579057361,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579236993,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614308325,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307534,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330732,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366505,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450350,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479615,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533589,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669137,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:copy_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614388037,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579902312,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579924940,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:update_sched_domain_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991261,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580015861,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580021807,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056299,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067216,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580148887,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580239858,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614410445,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614413533,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580665606,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305290,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_setup_cpumasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614432051,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092637,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586066305,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586072892,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586249839,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586282804,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859628,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588796927,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588816420,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588824600,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589055723,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579015584,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615172595,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275489,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615235973,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355878,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385884,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427277,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515342,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545887,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579605957,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746191,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:copy_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615321751,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580018411,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580048043,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:update_sched_domain_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123197,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580148021,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154047,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580188763,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580200736,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293415,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342388,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580389954,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615346751,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615349984,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580840296,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550058,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_setup_cpumasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615372107,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986847,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_cpu_affinity",
        "fs/io-wq.c:io_wq_cpu_affinity",
        "fs/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585540237,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586558861,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586567824,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586760223,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586797059,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587422844,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589489328,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509816,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589518473,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773859,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:574",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579034202,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616938061,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329373,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617011801,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418885,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451673,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495309,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599021,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634486,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698869,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579850435,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:copy_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617104147,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617107289,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup_type",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580264355,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293487,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580299823,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580339184,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580353939,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501927,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580555635,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580609431,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617131975,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617135446,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069550,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581903085,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617160160,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586037220,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586694895,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587815272,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825386,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588037260,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588078398,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588736590,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590972400,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590994047,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591007760,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591284005,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591492081,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:609",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579063930,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627544729,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396349,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627643167,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502693,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539276,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593375,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711391,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749794,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824005,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579986696,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580156806,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627772348,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580470215,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580504111,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580511828,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580556517,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576275,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580752348,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580814115,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872008,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067337,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627810489,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375267,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582337031,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627845232,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586873076,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589160751,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589167772,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589415292,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589460319,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590222478,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592676775,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592700980,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592715632,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593033365,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593271796,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595856319,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:685",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579063802,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619290991,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407241,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579482280,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_stop_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514855,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552092,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579605988,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579724671,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579796354,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579873077,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039704,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_nice_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580219114,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619533985,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541698,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576116,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584223,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580629381,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648570,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
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
      "addr": 18446744071580834931,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897411,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957323,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157689,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619573737,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469902,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619585503,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:init_osnoise_tracer",
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374700,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582538559,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619622037,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587138863,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589453987,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589461256,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589714400,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589760177,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590542350,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593107495,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593131984,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593152512,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593485307,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register_full"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593727828,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596373199,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:737",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579088890,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621583549,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435897,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579512392,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_stop_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621707254,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:smp_init_primary_thread_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579543557,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579579868,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635252,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759535,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579830546,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911125,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081197,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_unbound_exclude_cpumask",
        "kernel/workqueue.c:workqueue_unbound_exclude_cpumask",
        "kernel/workqueue.c:workqueue_apply_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_pod_cpumask",
        "kernel/workqueue.c:wqattrs_actualize_cpumask",
        "kernel/workqueue.c:copy_workqueue_attrs",
        "kernel/workqueue.c:copy_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580267914,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580299352,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:should_we_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621832930,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:init_sched_groups_capacity",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580603557,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580640404,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648575,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580694533,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580713786,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
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
      "addr": 18446744071580924355,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580987939,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048907,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621859119,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_full_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263193,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/cpuset.c:reset_partition_data",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621876911,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576994,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create_systems",
        "kernel/trace/trace.c:tracing_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621888847,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:init_osnoise_tracer",
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582542028,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582707710,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_alloc",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621926181,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587424991,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:io_wq_cpu_affinity",
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588471434,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589761971,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589769256,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050192,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590099206,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590898382,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593860311,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593885263,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593906111,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594232561,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register_full"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594507988,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597266559,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490275620,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:crash_smp_send_stop",
        "arch/arm64/kernel/smp.c:smp_send_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490656168,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490818116,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490927852,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491057836,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491081248,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491169356,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491183688,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491226584,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491237696,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491305928,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491410912,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510911532,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510916680,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510920820,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492422280,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_setup_cpumasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496366528,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gic_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496378480,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496389212,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate",
        "drivers/irqchip/irq-gic-v3-its.c:its_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496411128,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496428688,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/irqchip/irq-ls-scfg-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497642868,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497663668,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498187908,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498219956,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511225708,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:register_cpufreq_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501303260,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501756680,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224451296,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:smp_send_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3224532704,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/arm/common/bL_switcher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3224732536,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 3224851636,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 3224947352,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3225062580,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 3225085428,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3225195828,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 3225206716,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3225241468,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3225250608,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225305136,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225406796,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 3243399368,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 3243404752,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 3243408916,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3226306424,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_setup_cpumasks"
      ],
      "caller_func": []
    },
    {
      "addr": 3229695964,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/irqchip/irq-hip04.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3229701968,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gic_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3229712448,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3229725144,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3229740012,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/irqchip/irq-armada-370-xp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3230952220,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3243871360,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:register_cpufreq_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 3233791516,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 3234308920,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3236459728,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282418452,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/powerpc/kernel/rtas.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282510896,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302494464,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/powerpc/platforms/pseries/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/smp.c:smp_init_pseries"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283479452,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283651132,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283781020,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283935836,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283966080,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284069008,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284085792,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284128468,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284138592,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284233360,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284358428,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302548956,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302555688,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302561328,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285692608,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_setup_cpumasks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291426212,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294834600,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302842528,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/powernv-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295202732,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297691968,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271351904,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/riscv/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/smp.c:smp_send_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271401728,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271492752,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271564482,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271651362,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271670208,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271721200,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271731402,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271761682,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271767828,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271816014,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270649266,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270651482,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270655110,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272510102,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_alloc_possible",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_setup_cpumasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275968478,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578977965,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604626867,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039873,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579225163,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604683114,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269750,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291913,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329497,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417142,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491909,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579623438,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725230,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579832927,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579852115,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952357,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579959270,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579992011,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580001480,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064695,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154443,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604780281,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604785092,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604788867,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033148,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585161059,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585167820,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585176084,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585291727,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585319968,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585896984,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587660650,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679715,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587684842,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589665581,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578972305,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579160091,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604650668,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205094,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227388,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263817,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346262,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420773,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551806,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579653790,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767503,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579787027,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890245,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897110,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579930683,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579940152,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580009543,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100555,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604741498,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_full_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604749196,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604754044,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604757795,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580979228,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585075251,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585082060,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585117780,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585244239,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756760,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587434522,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587453795,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587461130,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587572572,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel_mgmt.c:init_vp_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589391405,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578977549,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604704675,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039457,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226235,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604760698,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270950,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293113,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329417,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417062,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491829,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579620718,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711982,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579820943,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579840339,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943893,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950806,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579983547,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579993016,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580055767,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580145915,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604857468,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604862279,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604866054,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024348,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585312099,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585319932,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585340964,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585480095,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585508656,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586086632,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587991802,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588010867,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588015994,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588222013,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590108957,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "cpumask_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578978141,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604704691,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043121,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579231643,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604760929,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276774,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301945,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337689,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426118,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478303,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579524325,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:init_cpu_online",
        "kernel/cpu.c:init_cpu_possible",
        "kernel/cpu.c:init_cpu_present"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654382,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_sysfs_prep_attrs",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_commit",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:alloc_workqueue_attrs",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579756841,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579866063,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885395,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990789,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997215,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_thread_check_affinity",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/manage.c:irq_do_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580030187,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039752,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106519,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:prof_cpu_mask_proc_write",
        "kernel/profile.c:profile_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197899,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604878966,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604883777,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604887591,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086364,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_alloc_pd",
        "kernel/padata.c:padata_alloc_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585418243,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585426076,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585448276,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585588271,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585616672,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586194920,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588107226,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588126339,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588131466,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357309,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590159281,
      "name": "cpumask_copy",
      "external": false,
      "loc": "include/linux/cpumask.h:590",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
void cpumask_copy(struct cpumask * dstp, const struct cpumask * srcp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void cpumask_copy(struct cpumask * dstp, const struct cpumask * srcp)
```
</details>
</li>
</ul>

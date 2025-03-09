# Function: <code>bitmap_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578892992,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978111,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578993213,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594987522,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579044998,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable",
        "arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174985,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595030371,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191814,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194339,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211474,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212906,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215042,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322293,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377621,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "addr": 18446744071579407354,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465227,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738691,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579743685,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580004033,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197252,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580204108,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:setup_vmstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582800016,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582964631,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583858129,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585884905,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
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
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578893392,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978093,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989837,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595150272,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579041074,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595195995,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192219,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194966,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212091,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213626,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215979,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327876,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390133,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "addr": 18446744071579419506,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595250295,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761140,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831816,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595275740,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580232650,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595283455,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251878,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076692,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188481,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586284992,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578893616,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980128,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991711,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595393039,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040998,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185926,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595438769,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203941,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206574,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223760,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225313,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227504,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343164,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410485,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "addr": 18446744071579439826,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518361,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579553997,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599592,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:load_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579787988,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083671,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cpuset.c:cpuset_init_smp",
        "kernel/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071595526562,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313793,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:trace_init"
      ]
    },
    {
      "addr": 18446744071580601074,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218421,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:cpumask_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584226352,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584241405,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584370001,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:211",
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
      "addr": 18446744071579497312,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580068928,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580276448,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578893082,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964126,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578984469,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596312234,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033824,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596359481,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201137,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201765,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204235,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221504,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223633,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225200,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337180,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398437,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "addr": 18446744071579427970,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506361,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579540383,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580089478,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071596445972,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580327369,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init"
      ]
    },
    {
      "addr": 18446744071580628424,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584298750,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584317821,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584452881,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588216291,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487040,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580074944,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580289312,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578894224,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578967406,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602629803,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134989,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602677442,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218876,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239296,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362616,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426453,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "addr": 18446744071579456260,
      "name": "bitmap_copy",
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
      "addr": 18446744071579533081,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579567990,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712802,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579817940,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580142187,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071580268567,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_init"
      ]
    },
    {
      "addr": 18446744071580380513,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init"
      ]
    },
    {
      "addr": 18446744071580709432,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584697816,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584717106,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584863489,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766243,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:220",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513744,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580127648,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580267856,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580342752,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578895944,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970135,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602798422,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579025457,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579144757,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212366,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602848905,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230965,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251841,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290117,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375029,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579440933,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "addr": 18446744071579471019,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579560659,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579596179,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851684,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580202042,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071602946018,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580442449,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init"
      ]
    },
    {
      "addr": 18446744071580844038,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584924145,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584944530,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585094567,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589144995,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:222",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541168,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580187328,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580403952,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578896452,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578968262,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604592502,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029547,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579210294,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236046,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604645710,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254661,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275640,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314329,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402693,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474437,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "addr": 18446744071579504687,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579597875,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579675211,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "addr": 18446744071579803602,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898676,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580253539,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071604743908,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580498097,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init"
      ]
    },
    {
      "addr": 18446744071580910054,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585028049,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048514,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585176734,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205351,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "addr": 18446744071586547205,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586551549,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:gen10g_config_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586563582,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_support_asym_pause",
        "drivers/net/phy/phy_device.c:phy_support_sym_pause",
        "drivers/net/phy/phy_device.c:phy_remove_link_mode",
        "drivers/net/phy/phy_device.c:phy_set_max_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587149442,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587555600,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774245,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589380131,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578160,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580235296,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580459248,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578898050,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578975213,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604688147,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037201,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224011,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249504,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_send_call_func_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604743435,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268678,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290057,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329481,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418131,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579492309,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "addr": 18446744071579523594,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579609070,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579707182,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579933493,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580305583,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071604845617,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554069,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers"
      ]
    },
    {
      "addr": 18446744071581009220,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231804,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585252676,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585389183,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585417536,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "addr": 18446744071585989648,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586796581,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586813934,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587414514,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587830827,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588079159,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589837181,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601664,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580286016,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580514304,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578899186,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977613,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700592,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039521,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226321,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604756843,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271046,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296105,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333593,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421315,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579472975,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518245,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446744071579549674,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647134,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579749278,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579983621,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580354447,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071604879635,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580601751,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers"
      ]
    },
    {
      "addr": 18446744071581064300,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585368348,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585390564,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585529695,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585558256,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446744071586136624,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586942309,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586960142,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587616274,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588035658,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588284967,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590063325,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627584,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580334240,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580561856,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578904135,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578987440,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609048836,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048849,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579244039,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609103226,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299984,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326441,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363113,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450539,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495199,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547637,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "addr": 18446744071579576406,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579679252,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579784984,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580011395,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580031925,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580427120,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071580568396,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_init"
      ]
    },
    {
      "addr": 18446744071580675966,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586069643,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586076280,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586100015,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586246991,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586278656,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "addr": 18446744071586892064,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587754709,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587778046,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588480130,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588896907,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589165611,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589891296,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:247",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683979,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580407120,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580567200,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580653888,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578900813,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988928,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612112180,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052145,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579236887,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612168142,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305502,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328044,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362137,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447803,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477631,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529333,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "addr": 18446744071579558022,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659380,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579777565,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579989789,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580015637,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580414608,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071580556268,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_init"
      ]
    },
    {
      "addr": 18446744071580563398,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580666886,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586191642,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586197720,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586365215,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586398752,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "addr": 18446744071586977044,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587814277,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587838081,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588510239,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588909467,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589161845,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589930432,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591279328,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580394400,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580555072,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580644512,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578909710,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997904,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614251994,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579057361,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579236999,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614308338,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307534,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330732,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366505,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450363,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479615,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533589,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "addr": 18446744071579562862,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669137,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:copy_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579784381,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity"
      ],
      "caller_func": [
        "kernel/sched/core.c:init_idle"
      ]
    },
    {
      "addr": 18446744071579902312,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "addr": 18446744071579924953,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:update_sched_domain_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991261,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580015861,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416208,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071580559589,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_init"
      ]
    },
    {
      "addr": 18446744071580566502,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580665606,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092637,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586066305,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586072892,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586249839,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586282804,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "addr": 18446744071586859636,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587693769,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587718241,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588393615,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588796927,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589055733,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589838387,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591222168,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071591224689,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580397344,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580558176,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580647712,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578912573,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579015584,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615172608,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275495,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615235986,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355878,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385884,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427277,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515355,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545887,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579605957,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "addr": 18446744071579638535,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746191,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:copy_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579878451,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": [
        "kernel/sched/core.c:init_idle"
      ]
    },
    {
      "addr": 18446744071580018411,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "addr": 18446744071580048056,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:update_sched_domain_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123197,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580148021,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580389954,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580580591,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071580729521,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_init"
      ]
    },
    {
      "addr": 18446744071580736356,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580840296,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986847,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586558861,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586567824,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586760223,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586797059,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "addr": 18446744071587422852,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588286291,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588311153,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589058527,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589489328,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773869,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590601139,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:251",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592102955,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071592106415,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580560016,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580728128,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580820672,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578918363,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034202,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616938074,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329390,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617011814,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418885,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451673,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495309,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599034,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634486,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698869,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "addr": 18446744071579734876,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579850435,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:wq_calc_node_cpumask",
        "kernel/workqueue.c:copy_workqueue_attrs",
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579994552,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": [
        "kernel/sched/core.c:init_idle"
      ]
    },
    {
      "addr": 18446744071580175378,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:update_sched_domain_debugfs"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:housekeeping_setup_type"
      ]
    },
    {
      "addr": 18446744071580264355,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293487,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580609431,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781506,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071580941949,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_init"
      ]
    },
    {
      "addr": 18446744071580948659,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581069550,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581903085,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586037220,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587815272,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825386,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588037260,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588078398,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "addr": 18446744071588736598,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589673515,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589700350,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590500530,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590972400,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591284009,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591492091,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592221391,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593870543,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071593874059,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071593880165,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580759616,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580940480,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581045216,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578934992,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063930,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627544742,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396366,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627643180,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502693,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539276,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593375,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711404,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749794,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824005,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "addr": 18446744071579861432,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579986696,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setaffinity"
      ]
    },
    {
      "addr": 18446744071627772348,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580504111,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872008,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067337,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581243011,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581375267,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_set_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582337031,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586873076,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589167772,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589415292,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589460319,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591284991,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get"
      ]
    },
    {
      "addr": 18446744071591317861,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_remove_link_mode",
        "drivers/net/phy/phy_device.c:phy_remove_link_mode"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause"
      ]
    },
    {
      "addr": 18446744071592147538,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592676775,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593033369,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593271806,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594051730,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595856319,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090016,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071591278800,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591306496,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578933088,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063802,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619291004,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407241,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_stop_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514886,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552092,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579605988,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579724684,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579796354,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579873077,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "addr": 18446744071579911563,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039714,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setaffinity"
      ]
    },
    {
      "addr": 18446744071619533999,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "addr": 18446744071580541714,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576116,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "addr": 18446744071580629398,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648599,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "addr": 18446744071580834948,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957339,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157689,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581338196,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581469902,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:init_osnoise_tracer",
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582374700,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582538559,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587138863,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589461256,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589714400,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589760177,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591634608,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get"
      ]
    },
    {
      "addr": 18446744071591644848,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active"
      ]
    },
    {
      "addr": 18446744071591665104,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_remove_link_mode",
        "drivers/net/phy/phy_device.c:phy_remove_link_mode"
      ]
    },
    {
      "addr": 18446744071592570962,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593107508,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "addr": 18446744071593131998,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
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
      "addr": 18446744071593152528,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593485323,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register_full"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593727838,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594430544,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ]
    },
    {
      "addr": 18446744071596373199,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:260",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145936,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071591634608,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591644848,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591665104,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071594430544,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578956039,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088890,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621583562,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435897,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_stop_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621707254,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:smp_init_primary_thread_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579543569,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579579868,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635252,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759548,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enter_uniprocessor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579830546,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911125,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "addr": 18446744071579950811,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081210,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:dup_user_cpus_ptr",
        "kernel/sched/core.c:__sched_core_flip"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setaffinity"
      ]
    },
    {
      "addr": 18446744071580299368,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:should_we_balance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621832944,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "addr": 18446744071580603561,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/power/energy_model.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_create_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580640404,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "addr": 18446744071580694550,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:default_affinity_write",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580713815,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "addr": 18446744071580924372,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048923,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621859132,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_full_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263193,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
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
        "kernel/cgroup/cpuset.c:reset_partition_data",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:guarantee_online_cpus"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask"
      ]
    },
    {
      "addr": 18446744071621876911,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445156,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581576994,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:init_osnoise_tracer",
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582542028,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582707710,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587424991,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "addr": 18446744071588471440,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "lib/group_cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/group_cpus.c:group_cpus_evenly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589761971,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589769256,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050192,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590099206,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592375200,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_up",
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get"
      ]
    },
    {
      "addr": 18446744071592385968,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active"
      ]
    },
    {
      "addr": 18446744071592407376,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_remove_link_mode",
        "drivers/net/phy/phy_device.c:phy_remove_link_mode"
      ]
    },
    {
      "addr": 18446744071593315586,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593860324,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "addr": 18446744071593885277,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
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
      "addr": 18446744071593906127,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594232570,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register_full"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594507998,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595232800,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "net/ethtool/linkmodes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/linkmodes.c:ethnl_auto_linkmodes"
      ]
    },
    {
      "addr": 18446744071597266559,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:237",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191344,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581226304,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071592375200,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071592385968,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071592407376,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595232800,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510814536,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:sve_init_vq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490275620,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446603336490698420,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490818116,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446603336490927852,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491169356,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491614000,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446603336510916680,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491900352,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers"
      ]
    },
    {
      "addr": 18446603336492422280,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gic_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496378480,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496389212,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/irqchip/irq-ls-scfg-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497642868,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497663668,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498187908,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498219956,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:register_cpufreq_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499925612,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499946208,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500769384,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501303260,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446603336501756688,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490796952,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336491598696,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336491862872,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224451296,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:smp_send_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3224532704,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/arm/common/bL_switcher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3224732536,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 3224766624,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3224851636,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 3224947352,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3225195828,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 3225571228,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 3243404752,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 3225842832,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers"
      ]
    },
    {
      "addr": 3226306424,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/irqchip/irq-hip04.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3229701968,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gic_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3229712448,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3229725144,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/irqchip/irq-armada-370-xp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3230952220,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 3243871360,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:register_cpufreq_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 3232469984,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 3232488504,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 3233281172,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233791516,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 3234308976,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3234815516,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_set_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user",
        "net/core/ethtool.c:load_link_ksettings_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 3236459728,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224835748,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3225558396,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3225807136,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282418452,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/powerpc/kernel/rtas.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282510896,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282837600,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/powerpc/mm/slice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302494464,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/powerpc/platforms/pseries/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/smp.c:smp_init_pseries"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283479452,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 13835058055283525936,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283651132,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 13835058055283781020,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284069008,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284605928,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 13835058055302555688,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284987888,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers"
      ]
    },
    {
      "addr": 13835058055285692608,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293243208,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293270440,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294220168,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294834600,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/cpufreq/powernv-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295202740,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297691968,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283661428,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 13835058055284584752,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 13835058055284936320,
      "name": "bitmap_copy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271351904,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/riscv/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/smp.c:smp_send_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271401728,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446743936271424314,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271492752,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271721200,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271731402,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277008872,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277030358,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277602704,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/input/evdev.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578899186,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977965,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604626880,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039873,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579225169,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604683127,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269750,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291913,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329497,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417155,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491909,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446744071579523338,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579623438,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579725230,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952357,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580323247,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071604785092,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570551,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers"
      ]
    },
    {
      "addr": 18446744071581033148,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585167820,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585176084,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585291727,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585319968,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446744071585896992,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586699317,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586717150,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587309090,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587660650,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589665581,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603888,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580303040,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580530656,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578893042,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972305,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579160097,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604650681,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205094,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227388,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263817,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346275,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420773,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446744071579452138,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551806,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579653790,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890245,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604741498,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_full_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270527,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071604754044,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580517223,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers"
      ]
    },
    {
      "addr": 18446744071580979228,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585082060,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585117780,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585244239,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756768,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586567669,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586585454,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587077474,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587434522,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587572572,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel_mgmt.c:init_vp_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589391405,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532528,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580250384,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580477536,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578899122,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977549,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604704688,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039457,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226241,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604760711,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270950,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293113,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329417,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417075,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491829,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446744071579523258,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579620718,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579711982,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943893,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314495,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071604862279,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580561799,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers"
      ]
    },
    {
      "addr": 18446744071581024348,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585319932,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585340964,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585480095,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585508656,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446744071586086640,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586896869,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586914702,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587567522,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587991802,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588222023,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590108957,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601168,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580294288,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580521904,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```

```json
{
  "name": "bitmap_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578899682,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978141,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604704704,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043121,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579231649,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604760942,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276774,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301945,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337689,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426131,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478303,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579524325,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446744071579556218,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654382,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
        "kernel/workqueue.c:alloc_workqueue_attrs"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579756841,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990789,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580369453,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_smp",
        "kernel/cgroup/cpuset.c:cpuset_init_smp"
      ]
    },
    {
      "addr": 18446744071604883777,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_init",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580618519,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_cpumask_write"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracer_alloc_buffers"
      ]
    },
    {
      "addr": 18446744071581086364,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585426076,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585448276,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585588271,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585616672,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "addr": 18446744071586194928,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587003253,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_get",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587021086,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_probe",
        "drivers/net/phy/phy_device.c:phy_set_sym_pause",
        "drivers/net/phy/phy_device.c:phy_advertise_supported",
        "drivers/net/phy/phy_device.c:phy_advertise_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679265,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_handle_get_val"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588107226,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
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
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357319,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590159281,
      "name": "bitmap_copy",
      "external": false,
      "loc": "include/linux/bitmap.h:231",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635104,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580348704,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580578384,
      "name": "bitmap_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void bitmap_copy(long unsigned int * dst, const long unsigned int * src, unsigned int nbits)
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

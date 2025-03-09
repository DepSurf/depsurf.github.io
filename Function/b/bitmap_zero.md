# Function: <code>bitmap_zero</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594941556,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578871478,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921818,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932015,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_assign_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999507,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid",
        "arch/x86/xen/apic.c:flat_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594987427,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595005488,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:init_amd_e400_c1e_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595011841,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356802,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595039890,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191731,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192991,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205294,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213368,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
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
      "addr": 18446744071579214897,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595067956,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360018,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376514,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488630,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:init_workqueues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579524466,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:init_rootdomain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:SyS_sched_setaffinity",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:sched_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611237,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595091154,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595091237,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648653,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579650223,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738735,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
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
      "addr": 18446744071579769577,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579772449,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579881187,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
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
      "addr": 18446744071579908041,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:hotplug_cfd",
        "kernel/smp.c:on_each_cpu_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580002987,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:generate_sched_domains",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580221918,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:__tracing_open",
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580491552,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541527,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722804,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580775548,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_register_ops",
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580795038,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580812393,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:mpol_parse_str"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580847912,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582794355,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808133,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_init_tags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811639,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583012394,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:__bitmap_parse",
        "lib/bitmap.c:__bitmap_parselist",
        "lib/bitmap.c:bitmap_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583129030,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583405807,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_mport_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583572370,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583750683,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583757130,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805941,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595246016,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583815443,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583838161,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583917701,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583974595,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:reset_buffer_flags",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584126224,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584484133,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584519171,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/base/regmap/regcache-lzo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-lzo.c:regcache_lzo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585594043,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585864924,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585872790,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595310823,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585892282,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585896333,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586263791,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586338711,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586402697,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586407358,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_xps_map",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586734589,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587029756,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:181",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
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
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595105341,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578871999,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578920234,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929311,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_assign_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996497,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:flat_vector_allocation_domain",
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595150180,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595169055,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:init_amd_e400_c1e_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595176446,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182728,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595205758,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192115,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197011,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data",
        "arch/x86/kernel/apic/vector.c:alloc_apic_chip_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206089,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214042,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215841,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595233750,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367181,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389964,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:disable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595249937,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595258582,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:SyS_sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595258744,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/fair.c:task_numa_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595258775,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595258858,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664253,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665757,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760494,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792777,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795633,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595268629,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579939775,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580037994,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580264744,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576237,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580630021,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580839986,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899593,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580918590,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950020,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973905,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070688,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087232,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_init_tags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583090775,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583303258,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:__bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583423494,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583723903,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_mport_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894683,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076830,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init",
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584083126,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584132236,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595427665,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584142601,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584167233,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584248869,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584310701,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:reset_buffer_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584461856,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595441108,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584830050,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584866241,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/base/regmap/regcache-lzo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-lzo.c:regcache_lzo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988107,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586266742,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586274235,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586283953,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586293014,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586296205,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/speedstep-centrino.c:centrino_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586688855,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586771527,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586845472,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586850148,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:show_xps_map",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587186831,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587477709,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
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
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595351109,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578871999,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578920506,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929791,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_assign_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998256,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:flat_vector_allocation_domain",
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193245,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595448645,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203859,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208714,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217753,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227392,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595477228,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385154,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410344,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599289,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:SyS_sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579622477,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786877,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579822838,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579941413,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580072449,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_css_alloc",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580307772,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342297,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580642502,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697208,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910548,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580967993,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580985347,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022554,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581047663,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182366,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202249,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "block/blk-mq-cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583422298,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:__bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583863439,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_mport_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584219893,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584226474,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584241441,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584280236,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595679240,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584323129,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584348509,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584430469,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584492675,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:reset_buffer_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584644106,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595693460,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585023275,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585059793,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/base/regmap/regcache-lzo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-lzo.c:regcache_lzo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586176235,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586471246,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586478342,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586488398,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586874785,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586958071,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587036208,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587387743,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587680973,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596268788,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578871327,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913801,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923073,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_assign_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578959776,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:flat_vector_allocation_domain",
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121587,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191477,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ]
    },
    {
      "addr": 18446744071596369547,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201939,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206243,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_irq_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215113,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224114,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225088,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323780,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338532,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071579372658,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397742,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578037,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601873,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683821,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784402,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579821627,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949669,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975572,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580086977,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580320902,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580355022,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580675078,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731002,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581014985,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581031299,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068506,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071581096095,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583016859,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246838,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583443451,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:__bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583912175,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_mport_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584291686,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584298569,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584317459,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584360103,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584364455,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 18446744071584403090,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584429822,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584514757,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584575604,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584727194,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596617982,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585108267,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585740688,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_link_ksettings",
        "drivers/net/tun.c:tun_get_link_ksettings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586267563,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586602906,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612845,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586999279,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587082695,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587164208,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587527041,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587832056,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:190",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185840,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579338532,
      "name": "bitmap_zero.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071581052336,
      "name": "bitmap_zero.constprop.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071584364455,
      "name": "bitmap_zero.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602584725,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578872351,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915881,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925169,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_assign_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578963235,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578987258,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135527,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207311,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ]
    },
    {
      "addr": 18446744071602687674,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217443,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232801,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348764,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363972,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071579399650,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425795,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579607733,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634225,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712051,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579817761,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579857003,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579995381,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022052,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580139885,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580268419,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270293,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580374037,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408726,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580760326,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817068,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581123999,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140918,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179642,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071581208367,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181883,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425991,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583623397,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:__bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584175519,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_mport_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584689817,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584697493,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584716765,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584765895,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584770237,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 18446744071584809992,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584837758,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584924789,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584987636,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585141658,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602948044,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585534459,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586174624,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_link_ksettings",
        "drivers/net/tun.c:tun_get_link_ksettings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586730991,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587061709,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086202,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587095901,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587497967,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587584378,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588049889,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588344962,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201664,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579363972,
      "name": "bitmap_zero.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071581163472,
      "name": "bitmap_zero.constprop.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071584770237,
      "name": "bitmap_zero.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602752902,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578874302,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578918135,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578927408,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_assign_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578965808,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989545,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144845,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218696,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ]
    },
    {
      "addr": 18446744071602859121,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229728,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244999,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360476,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376580,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071602905393,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413410,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579440215,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579617454,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656258,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579744010,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851505,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890616,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047487,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580076123,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197874,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580328675,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580330565,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580435403,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469724,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896255,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954076,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266051,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282201,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324980,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351652,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583388171,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583637253,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583839920,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:__bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130306,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584393551,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_mport_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584916135,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584923963,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584944189,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584994247,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584998511,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 18446744071585040484,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585068413,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585154037,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585220790,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585375834,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603120827,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778119,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586428891,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586997424,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587359917,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587384368,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587394266,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587802698,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587893018,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588406735,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588701557,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:202",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213552,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579376580,
      "name": "bitmap_zero.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579432400,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584998511,
      "name": "bitmap_zero.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604546977,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578919791,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578963904,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988176,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210382,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242376,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ]
    },
    {
      "addr": 18446744071604656058,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253424,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268775,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387988,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404244,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071604703574,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446175,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579473719,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579645742,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698706,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579783945,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898497,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579937688,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580094319,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123435,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580255852,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580381941,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580383829,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580491067,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525804,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580970975,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030268,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349232,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366793,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409100,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435476,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582139886,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583742313,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922912,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:__bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584214798,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585020039,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_throttling_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585027867,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048173,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585098599,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585102987,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585264853,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585340166,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604923551,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585911319,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_mem_sect_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586545829,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586551525,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:gen10g_config_init",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562091,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586578539,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587158656,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587539757,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587564480,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574234,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587937930,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588036058,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588598735,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588920213,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237232,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579404244,
      "name": "bitmap_zero.constprop.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579465936,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585102987,
      "name": "bitmap_zero.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604641021,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578925155,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578970832,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998105,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224102,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256307,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071604753246,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267504,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283032,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403457,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419675,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071604803901,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462535,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490949,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579678464,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579731265,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579812512,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579933310,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976268,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580138191,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580168920,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580307000,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580434646,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580436665,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580546903,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582228,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094264,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388869,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581459648,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475183,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521272,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550429,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582300160,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583931226,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584105059,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584403631,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585223702,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231638,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605010527,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585252336,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585302651,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585307531,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585475269,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585554774,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605032388,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586152389,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:unregister_memory_block_under_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586793701,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586812865,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586830283,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587423451,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587814557,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587840254,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587850160,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588247370,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588319914,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588347710,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589010294,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589362016,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:215",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251552,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579419675,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579483792,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585307531,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578927123,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973296,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999609,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226412,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257971,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071604766873,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269152,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285496,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406705,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422843,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071604829622,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465702,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:reset_with_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579489223,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579516881,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579711792,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579774529,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860301,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579983438,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580025788,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580186335,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580216856,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580355864,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580483414,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485433,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580594455,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580629332,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151224,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450437,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523744,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539328,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446744071581585311,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615405,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582399184,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584034567,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584227955,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584539309,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585360134,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585368182,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585377653,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585390224,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585440619,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585445499,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585615973,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585698310,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605068999,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586940037,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586947157,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959073,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586976363,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587626507,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588019757,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045086,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054976,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588451530,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588526570,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588554158,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589234937,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589586128,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253264,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579422843,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579509776,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581564894,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071585445499,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578932794,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578982960,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000543,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244126,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279553,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071609112870,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297072,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309587,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417210,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453100,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071609166844,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579486507,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:reset_with_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517479,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579546197,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ]
    },
    {
      "addr": 18446744071579753698,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579812768,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899417,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_balance_mask"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580030573,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:desc_set_defaults"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580076284,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580251119,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580284808,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580428633,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580568278,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570339,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580693468,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730336,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581337139,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731008,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581750130,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446744071581797247,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071581827513,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582688971,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584429342,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584634323,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585212249,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586069270,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586076114,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586086116,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586099847,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586157643,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609343927,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586339637,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586431863,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609358103,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587754005,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587762709,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774975,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587795428,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587803323,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588489086,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588879245,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588905374,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588915728,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589319770,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589406554,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589861057,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32",
        "net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589886114,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590210691,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590589312,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:235",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278656,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579453100,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579537632,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579895472,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581775492,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071581776736,
      "name": "bitmap_zero.constprop.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578933978,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578984720,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579002655,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236974,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271218,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286929,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071612177631,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302320,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315267,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417290,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591272870,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071612236871,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500087,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527905,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ]
    },
    {
      "addr": 18446744071579738814,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803312,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579894137,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_balance_mask"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580014493,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:desc_set_defaults"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580058412,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580234943,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580268328,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416145,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580556150,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580558035,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580684268,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580719675,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378275,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778656,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581798274,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446744071581845151,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071581874985,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_map"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584545742,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584753368,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585363924,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586191222,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586197554,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586207011,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586220431,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586275643,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612415081,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586457893,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586546919,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586620664,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:reset_terminal"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612429280,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587813557,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587821893,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587834159,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587851621,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587853396,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587861083,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588518366,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892269,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588917950,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588928243,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589318818,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589349108,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589407402,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589900977,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32",
        "net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589925410,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590261347,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590649008,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286032,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071591272870,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579519792,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579890176,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071591332427,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071581824256,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586615728,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881144,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578938890,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578993824,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009951,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579237086,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272610,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289326,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071614318067,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305184,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317121,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420410,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591215750,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071614377533,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503434,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532157,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ]
    },
    {
      "addr": 18446744071579747243,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579809699,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905604,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580015681,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580059122,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580194533,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_percpu",
        "kernel/time/clocksource.c:clocksource_verify_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580240255,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580272633,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580417745,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559463,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580561299,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580688184,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724765,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399092,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614431878,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806224,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581826402,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446744071581875932,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071581905257,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:get_map"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584578186,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584781816,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585247502,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586065851,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586072483,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586081731,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586095012,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586149455,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614555959,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586223951,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586341653,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586426993,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586504904,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:reset_terminal"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614570424,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587693045,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587701253,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587713055,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587729941,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587732554,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587739195,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588401419,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588781485,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588806558,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588816565,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589214482,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248781,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589303434,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589807953,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32",
        "net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589833262,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590175090,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590574494,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591136961,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:233",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:pm_nl_init_net",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288560,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071591215750,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579523072,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579898816,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071591275111,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071581854896,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586500000,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578884852,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578946074,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579011200,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579027979,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275582,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315489,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333919,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071615246719,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353216,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367428,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579483962,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592092219,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071615309792,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579574193,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579604445,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ]
    },
    {
      "addr": 18446744071579824619,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906851,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580023330,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:asym_cpu_capacity_scan",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": [
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580147811,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580191682,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342150,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390867,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580424527,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582161,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580729395,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731349,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580863256,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905015,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649284,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615371934,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091488,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115698,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446744071582167500,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_new_preferred"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071582201678,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__fill_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582903540,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584991146,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585212280,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585703428,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586558363,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586567387,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586578835,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586592926,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586651119,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615509706,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586730245,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586861797,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586953971,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587040984,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:reset_terminal"
      ],
      "caller_func": [
        "drivers/tty/vt/vt.c:do_con_trol"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615525217,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588284373,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588292885,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588305647,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588323445,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588326634,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588334427,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589067536,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589473725,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589499198,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509970,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936818,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589973661,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590031570,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590570401,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32",
        "net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590596158,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ethtool/features.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590955826,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591386398,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591992040,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579332608,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071592092219,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579594704,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580014096,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071592210980,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071582147200,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587032144,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578882562,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578954747,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971902,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_assign_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029584,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047869,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329478,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579373442,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395482,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617023205,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415424,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430020,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563191,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593859289,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071617090936,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579666712,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697185,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:thaw_secondary_cpus"
      ]
    },
    {
      "addr": 18446744071579937701,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580019204,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580195422,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580292731,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342008,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580555379,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580608915,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580647325,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580782801,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941809,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944101,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581093061,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140527,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384964,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:alloc_new_pack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582002689,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617159984,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582531956,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582555485,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446744071582624820,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_new_preferred"
      ],
      "caller_func": [
        "mm/mempolicy.c:numa_policy_init"
      ]
    },
    {
      "addr": 18446744071582666222,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__fill_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585421615,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585702783,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594112590,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586049012,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586871306,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586893750,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587227023,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_mport_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587814761,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825195,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587838867,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587851637,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587918525,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617313562,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587989333,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588003045,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588147269,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588245138,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588361843,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588435674,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617329975,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589668309,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode",
        "drivers/net/phy/phy.c:phy_speed_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589678853,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589693488,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_read_lpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589713845,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589717606,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/bcm84881.c:bcm84881_read_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589729979,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590512512,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590952249,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590973578,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590982046,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590994199,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591469697,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591491117,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591575674,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592187809,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32",
        "net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592216092,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592587747,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593062146,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593731478,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593742902,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:238",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593859289,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579686704,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071593989431,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582601888,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578887758,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971515,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578990078,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_assign_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059088,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078614,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396454,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434242,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474690,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627658689,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579498192,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514036,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579670841,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627727749,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627749059,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786341,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579822278,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580098965,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580188097,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580388400,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580503298,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559512,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813857,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580873459,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580914233,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581065708,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581235385,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581238241,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400613,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453478,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733680,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:alloc_new_pack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440904,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582513150,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627845051,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583046788,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583083229,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583149220,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_new_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193102,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__fill_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583353600,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586482559,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586746063,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587032295,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588019658,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045510,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588462058,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589160919,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589167967,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589181207,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589198079,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589270690,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628034842,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589354581,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589374169,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589540725,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589657554,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589783048,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589863690,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628056581,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591280373,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode",
        "drivers/net/phy/phy.c:phy_speed_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591289461,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591316517,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_read_lpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591334918,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/bcm84881.c:bcm84881_read_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591351051,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592159968,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592653961,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592677542,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592687644,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592701132,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593239334,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593271176,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593364613,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594013269,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594046060,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594449881,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594954162,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595665638,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595679446,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
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
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578885790,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970731,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989294,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_assign_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579058976,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078409,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407380,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446290,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579482431,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_stop_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488130,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619415599,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579510368,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579526212,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579684788,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619486949,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619508563,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833307,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871398,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580156933,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580253285,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580456992,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574871,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580632984,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897153,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580956755,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999395,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581156076,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330649,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333249,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/watchdog_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581495427,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe",
        "kernel/trace/trace.c:close_pipe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550982,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892839,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:alloc_new_pack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374117,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646248,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582715033,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619621867,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125156,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583255572,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583293837,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583359516,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_new_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583410846,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__fill_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583572907,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583795356,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:mm_init_cid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586730127,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016094,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_register_iowq_aff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587287447,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588294058,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588320120,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588741210,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589454128,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589461431,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589475271,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589492239,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589567314,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619800004,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589653269,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589672800,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589842021,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589961182,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590087927,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590172426,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619822693,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635212,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591646229,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591676698,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_read_lpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591696438,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/bcm84881.c:bcm84881_read_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591712827,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591743184,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592583424,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593084761,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593108312,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593118636,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593132161,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593700557,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593727208,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827057,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594389829,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594424412,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594841592,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595346642,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596173894,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596189622,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:240",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
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
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578908094,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995499,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events",
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014174,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_assign_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104185,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_drop_mm_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436036,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579476050,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579512649,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:native_stop_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518146,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621711127,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579554980,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719300,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621783269,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621805395,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871147,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579909318,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621818944,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_unbound_cpus_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580202165,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580303029,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580516640,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:asym_cpu_capacity_scan",
        "kernel/sched/build_utility.c:build_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:sched_domain_debug_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580639158,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698136,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580987681,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048339,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621859550,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095539,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581261968,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_exclusive_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:reset_partition_data",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437161,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439761,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/watchdog_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606220,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe",
        "kernel/trace/trace.c:close_pipe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663206,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:move_to_next_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022903,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:alloc_new_pack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541445,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817384,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883924,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621926011,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583308147,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583391230,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__fill_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583530525,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583595964,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_new_preferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583766353,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:hpage_collapse_scan_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584001452,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:mm_init_cid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587001887,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587410798,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "io_uring/register.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/register.c:io_register_iowq_aff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587573319,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587633218,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "lib/bitmap-str.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap-str.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588587896,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588611418,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589044330,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589762112,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589769431,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781703,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_update_target_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589799807,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589876690,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622108052,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589963701,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_get_any_slave_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589983504,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179077,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590300158,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590427102,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:reset_terminal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590512602,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622131397,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592375804,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592387557,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592419098,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:phy_init_hw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592439494,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/net/phy/bcm84881.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/bcm84881.c:bcm84881_read_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592456523,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592486771,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593328160,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593837161,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593861255,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593871468,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593885440,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594478301,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594507368,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:flush_all_backlogs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594608654,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595190869,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595226655,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595651672,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596187378,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597046726,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit",
        "net/mptcp/pm_netlink.c:fill_remote_addresses_vec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597065065,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:217",
      "file": "net/mptcp/pm_userspace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490185276,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:sve_probe_vqs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/arm64/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/arm64/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/arm64/kernel/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490238448,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/traps.c:dump_backtrace",
        "arch/arm64/kernel/traps.c:dump_backtrace"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/arm64/kernel/return_address.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/arm64/kernel/perf_callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490361592,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/arm64/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/numa.c:numa_init",
        "arch/arm64/mm/numa.c:numa_init",
        "arch/arm64/mm/numa.c:numa_init",
        "arch/arm64/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446603336490380000,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_init",
        "virt/kvm/kvm_main.c:kvm_make_all_cpus_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490436324,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490609984,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "virt/kvm/arm/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/pmu.c:kvm_pmu_vcpu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490621980,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490654512,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446603336490824400,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_numa_init"
      ]
    },
    {
      "addr": 18446603336490928104,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__arm64_sys_sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510886024,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510886092,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510886208,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491049028,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491051160,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491061796,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491098728,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:__arm64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491168964,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491227016,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491237848,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
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
      "addr": 18446603336491411592,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init"
      ]
    },
    {
      "addr": 18446603336491456440,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491613960,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446603336491759620,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491835704,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491892380,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491933576,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510935616,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_all_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492527996,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492949980,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492966712,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446603336493017656,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:get_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493058784,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493999504,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495866064,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496102856,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496326764,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496411180,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496633444,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496725352,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497125264,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pci/controller/pci-xgene-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497128100,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pci/controller/pcie-iproc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/video/fbdev/mx3fb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497428040,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497642008,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497651676,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497663164,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map",
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497723428,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497727924,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498057752,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/mv_xor_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498132168,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/soc/qcom/rpmh-rsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe",
        "drivers/soc/qcom/rpmh-rsc.c:tcs_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498377844,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511212984,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499101568,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499200048,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499925476,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499929912,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499945064,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499967264,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500781840,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501276352,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501302968,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501313920,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501498284,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/firmware/ti_sci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/ti_sci.c:ti_sci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511289548,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/firmware/efi/arm-runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501597160,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_alias_get_alias_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501761404,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci5xx_pmu_write_counters",
        "drivers/perf/arm-cci.c:__cci_pmu_enable_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501792872,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501975456,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502058080,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502103412,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502262124,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502853100,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503260372,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490238448,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490361592,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336490645592,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446603336490796976,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446603336491063776,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446603336491410664,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446603336491597176,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336492966712,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336497727924,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224511732,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/arm/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/context.c:check_and_switch_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3224532904,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/arm/common/bL_switcher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3224701724,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224722580,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243373108,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 3243373200,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 3225054716,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225056564,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225057976,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225195456,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225250820,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225407416,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init"
      ]
    },
    {
      "addr": 3225441604,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3225571792,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 3225708024,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 3225777760,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3225834756,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3225867780,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3243425076,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3226395148,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 3226733836,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 3226771388,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 3227463568,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229213220,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 3229427180,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 3229660380,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3229941468,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3230015832,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/video/fbdev/mx3fb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230855008,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/ti/edma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/dma/ti/edma.c:edma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/soc/qcom/spm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/soc/tegra/fuse/fuse-tegra20.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231055764,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243857548,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3231458980,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/iommu/ipmmu-vmsa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231654996,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3231731800,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/mtd/nand/raw/omap2.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232468728,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 3232474272,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 3232487500,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232508292,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3233292880,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 3233765700,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3233791224,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
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
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243941956,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/firmware/efi/arm-runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services"
      ],
      "caller_func": []
    },
    {
      "addr": 3234126024,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_alias_get_alias_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3234309680,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci5xx_pmu_write_counters",
        "drivers/perf/arm-cci.c:__cci_pmu_enable_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "sound/core/pcm_dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234811012,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 3234844656,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235546476,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 3235936748,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224722580,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3225057400,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3225407416,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3225556564,
      "name": "bitmap_zero",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302391028,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/powerpc/kernel/setup-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282510832,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi"
      ],
      "caller_func": [
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus"
      ]
    },
    {
      "addr": 13835058055282777660,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/powerpc/mm/book3s64/radix_tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_tlb.c:exit_flush_lazy_tlbs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282832580,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282837692,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/powerpc/mm/slice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/mm/slice.c:slice_range_to_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282943028,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/powerpc/sysdev/xive/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282981056,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/powerpc/platforms/powernv/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283080480,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/powerpc/platforms/powernv/opal-imc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283187516,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/powerpc/platforms/pseries/hotplug-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283438444,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283477288,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 13835058055283659220,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283781348,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__do_sys_sched_setaffinity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302519200,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/sched/fair.c:task_numa_placement"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302519308,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302519484,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283925732,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283927916,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283940712,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:sched_init_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain",
        "kernel/sched/topology.c:init_rootdomain"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283987056,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_global_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284068484,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284128808,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284137764,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
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
      "addr": 13835058055284359808,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init",
        "kernel/time/tick-broadcast.c:tick_broadcast_init"
      ]
    },
    {
      "addr": 13835058055284407340,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:on_each_cpu_cond_mask",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284605836,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 13835058055284801476,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284905020,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284975000,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285031988,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302581428,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285822636,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286246140,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286364204,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286391468,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 13835058055286452192,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286500360,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287648436,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290065404,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290348892,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290644956,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290815672,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291557948,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055302774888,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292287744,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293241960,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293248192,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293266976,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_read_lpa"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293297648,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294234436,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294799696,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294834228,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294847460,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295022452,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_alias_get_alias_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295403380,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295508732,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295559676,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295756804,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:show_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296507532,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297010516,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282509424,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 13835058055283466752,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055283942636,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 13835058055284359616,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 13835058055284581760,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 13835058055286386304,
      "name": "bitmap_zero.constprop.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271350856,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/riscv/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/smp.c:riscv_cpuid_to_hartid_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271379532,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270626542,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:init_sched_rt_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270626672,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:init_sched_dl_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271645336,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271646988,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271647252,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
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
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271721716,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271767964,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271911432,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smpcfd_prepare_cpu",
        "kernel/smp.c:smpcfd_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272012842,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset",
        "kernel/cgroup/cpuset.c:alloc_trial_cpuset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272137818,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272181234,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe",
        "kernel/trace/trace.c:__tracing_open"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272865024,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270695334,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272927140,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273514576,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274991638,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275168554,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/cpu_rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275482682,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276042738,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276421368,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276491634,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology",
        "drivers/base/arch_topology.c:clear_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277009518,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277015334,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277029480,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_read_lpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277045964,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277610650,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277951160,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278067902,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_alias_get_alias_list"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278337436,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278365458,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278965918,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279289304,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578927123,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973648,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999961,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225260,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256675,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071604693152,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267856,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284200,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402545,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418683,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071604743502,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462887,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490545,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579687968,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579750385,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579832653,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579952174,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994524,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155135,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185656,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580324664,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580452214,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580454233,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580563255,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580598132,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120072,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419285,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492480,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581508064,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446744071581554047,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584141,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582367920,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584003303,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584196691,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584496237,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585160678,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585167654,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585169621,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585175744,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585203147,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585208027,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585377621,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585459334,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604968622,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586697045,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586704165,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586716081,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586733371,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587319323,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587644749,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670078,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679968,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588058314,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588133306,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588160894,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588841321,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589190496,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251968,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579418683,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579483440,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581533630,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071585208027,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578923715,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579160188,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191891,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071604660672,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203280,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219489,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331985,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579347819,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071604711119,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391847,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419409,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579616432,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579680769,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767229,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890062,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579933196,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580101247,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604741594,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580133139,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271932,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580399286,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580401305,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580509959,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580544612,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067064,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361797,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434720,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450256,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446744071581495695,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525661,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305616,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583939127,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584131907,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584434365,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585074870,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585081894,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585112613,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585117440,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585155355,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585160235,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585329366,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604932957,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586565381,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586572485,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586584385,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586600587,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587087691,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587418621,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587443950,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587454048,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587572734,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel_mgmt.c:init_vp_index",
        "drivers/hv/channel_mgmt.c:init_vp_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587771402,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587846138,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587873726,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588553257,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588915488,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187216,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579347819,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579412320,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581475406,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071585160235,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578927059,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973232,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999545,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226332,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257875,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071604770736,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269056,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285400,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402465,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418603,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071604821069,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462807,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490465,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579685008,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734897,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579820669,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943710,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579986060,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580146607,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580177128,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580315912,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580443462,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580445481,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554503,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580589380,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581111272,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410485,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581483792,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499376,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446744071581545359,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575453,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358400,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583987063,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584180451,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584490973,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585311718,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585319766,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585340624,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585391019,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585395899,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585566373,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585648710,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605049322,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586894597,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586901717,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586913633,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586930923,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587577755,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587975901,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001230,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588011120,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588390090,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588465130,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588492718,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589277497,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589627360,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253168,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579418603,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579483360,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581524942,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071585395899,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_zero",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578927635,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_schedule_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973824,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/xen/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/apic.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579002347,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231740,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263475,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071604770993,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274656,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291288,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411304,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427659,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    },
    {
      "addr": 18446744071604833779,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579471030,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:reset_with_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495223,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579522865,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579720224,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_user_cpu_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579782561,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865789,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990606,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032716,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/irq/migration.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/migration.c:irq_move_masked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580198591,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580229320,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580370665,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:generate_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580499094,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501113,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/watchdog_hld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580611223,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646276,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173752,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474277,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:build_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548864,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581566000,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages"
      ]
    },
    {
      "addr": 18446744071581610479,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_parse_str",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:migrate_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581640701,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438032,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584089367,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584284787,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_fold",
        "lib/bitmap.c:bitmap_onto",
        "lib/bitmap.c:bitmap_remap",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584597213,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585417862,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585425910,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585435381,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585447936,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_get_psd_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585498363,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/quirks.c:quirk_cmi8330_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585503243,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/pnp/pnpacpi/rsparser.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource"
      ]
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585674341,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756838,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:n_tty_flush_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605073193,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_uart_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587000981,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587008101,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy-c45.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587020017,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587039691,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_setup",
        "drivers/net/tun.c:tun_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587689691,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588091277,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/opp/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588116670,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588126592,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588525834,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588602042,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_set_settings",
        "net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588630238,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589312521,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589676304,
      "name": "bitmap_zero",
      "external": false,
      "loc": "include/linux/bitmap.h:219",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_dev_get_saddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258736,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579427659,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579515104,
      "name": "bitmap_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581589855,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071585503243,
      "name": "bitmap_zero.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```
</details>
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
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void bitmap_zero(long unsigned int * dst, unsigned int nbits)
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

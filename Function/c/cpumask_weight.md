# Function: <code>cpumask_weight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594958570,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579019328,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594987546,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068859,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075924,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579099279,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579112971,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130569,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172515,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174168,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579175281,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579177887,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:smp_announce",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:native_smp_cpus_done",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183748,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595037543,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214851,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229413,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:crash_load_segments"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579322337,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374869,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:disable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465474,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_cpu_up_callback",
        "kernel/workqueue.c:init_workqueues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595083750,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidmap_init",
        "kernel/pid.c:pidmap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579523238,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sd_degenerate",
        "kernel/sched/core.c:register_sched_domain_sysctl",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:set_cpus_allowed_common",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579574630,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:get_update_sysctl_factor",
        "kernel/sched/fair.c:update_max_interval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579629889,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595091486,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710190,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595093333,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579785425,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579875727,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880362,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_unfreeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889128,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595100982,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579909306,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_announce",
        "kernel/smp.c:smp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580025105,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:__stop_cpus",
        "kernel/stop_machine.c:stop_machine",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580087307,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580089467,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580117887,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580123798,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580128090,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580207888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_event_info",
        "kernel/trace/trace.c:print_trace_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580423152,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580457318,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_reorder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580464319,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "kernel/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/membarrier.c:SyS_membarrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580530350,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:writeback_set_ratelimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580604070,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:calculate_pressure_threshold",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:refresh_zone_stat_thresholds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587354690,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580733940,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:set_iounmap_nonlazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595147841,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580863670,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321548,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479750,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:stat_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582945782,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038075,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039755,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:bucket_table_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595222462,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583572964,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747736,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm",
        "drivers/acpi/processor_idle.c:acpi_idle_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584722139,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585076912,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_set_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595295153,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585451876,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585680521,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585848184,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585871913,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585875940,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585879326,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_timer",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585884300,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585888136,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595313507,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586274390,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_get_num_default_rss_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586402882,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586408871,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586586806,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:474",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
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
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595120064,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932492,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579011839,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579021523,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595166991,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072610,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579098803,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579112802,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129928,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172899,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174547,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579175745,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579182561,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_smp_cpus_done",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:smp_announce",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184354,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595203367,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215763,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229108,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:crash_load_segments"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364948,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579328396,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:_cpu_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595250722,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595251113,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pidmap_init",
        "kernel/pid.c:pidmap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579574160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:sd_degenerate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579639222,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_max_interval",
        "kernel/sched/fair.c:get_update_sysctl_factor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579644530,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579677510,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595259143,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730078,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595261161,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759592,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/printk/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/nmi.c:printk_nmi_flush_on_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799119,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_mask",
        "kernel/irq/affinity.c:irq_create_affinity_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823414,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579907847,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910122,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579918727,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595268968,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579940182,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_announce",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580059714,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine",
        "kernel/stop_machine.c:__stop_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580120779,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580123013,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580151823,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580157834,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580162127,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580260726,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_header",
        "kernel/trace/trace.c:print_event_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580421018,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580443536,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448873,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450635,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580496323,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580533674,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580539839,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/membarrier.c:SyS_membarrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580616542,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:writeback_set_ratelimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580707347,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587855402,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595304106,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580859574,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:set_iounmap_nonlazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595319096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580992524,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581489677,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664166,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:stat_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582144454,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "fs/squashfs/decompressor_multi_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583233086,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583330667,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332498,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:bucket_table_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595399751,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583895282,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584074264,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595467919,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlblk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585074466,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585468624,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595478294,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585847444,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586082562,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586242665,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586278833,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586284502,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586288230,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595496863,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586703926,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586845643,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586851705,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587031158,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595362800,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018973,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023267,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself"
      ],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus",
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579064838,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ]
    },
    {
      "addr": 18446744071579071986,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579096931,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579111347,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124908,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137166,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183875,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184899,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579186169,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579193056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_smp_cpus_done"
      ]
    },
    {
      "addr": 18446744071579195720,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381872,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579227795,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579241532,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:crash_load_segments"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383034,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579343736,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579409812,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514082,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071580607223,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidmap_init",
        "kernel/pid.c:pidmap_init"
      ]
    },
    {
      "addr": 18446744071579599698,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:build_sched_domains"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:build_sched_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:sd_degenerate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ]
    },
    {
      "addr": 18446744071579615840,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_max_interval",
        "kernel/sched/fair.c:get_update_sysctl_factor"
      ]
    },
    {
      "addr": 18446744071579669209,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579702134,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714991,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595504104,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579757470,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580607682,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071579785688,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/printk/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/nmi.c:printk_nmi_flush_on_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827695,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579852454,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938298,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579940586,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949287,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595514655,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579970220,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": [
        "kernel/smp.c:smp_init",
        "kernel/smp.c:smp_init"
      ]
    },
    {
      "addr": 18446744071580099826,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine",
        "kernel/stop_machine.c:__stop_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580161099,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580163349,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580192223,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580198266,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580202547,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580303766,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_header",
        "kernel/trace/trace.c:print_event_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580470464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580504234,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    },
    {
      "addr": 18446744071580506796,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580507915,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580511380,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559779,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580598676,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580603871,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "kernel/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/membarrier.c:SyS_membarrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580683598,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:writeback_set_ratelimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580773461,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold"
      ],
      "caller_func": [
        "mm/vmstat.c:setup_vmstat"
      ]
    },
    {
      "addr": 18446744071588070088,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208387,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071580922724,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595567291,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581066283,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571950,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752726,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:stat_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583348317,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455637,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583457902,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583531977,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034728,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584215503,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    },
    {
      "addr": 18446744071595720435,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlblk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585259739,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595731244,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586032668,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_msix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586281803,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586445326,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586483080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586489032,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586494634,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_init",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595750065,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586897062,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587036408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush",
        "net/core/flow.c:flow_cache_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587042711,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587227270,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:478",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019584,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579061664,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579187536,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579381872,
      "name": "cpumask_weight.constprop.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579342144,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579500608,
      "name": "cpumask_weight.constprop.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580607223,
      "name": "cpumask_weight.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579565552,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579615840,
      "name": "cpumask_weight.constprop.91",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580607682,
      "name": "cpumask_weight.constprop.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579968224,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580497856,
      "name": "cpumask_weight.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580768032,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581208387,
      "name": "cpumask_weight.constprop.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584215503,
      "name": "cpumask_weight.constprop.11",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596280847,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579011563,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013243,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579015867,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579056566,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ]
    },
    {
      "addr": 18446744071579063945,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579088467,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579103445,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120727,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136023,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158127,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/cpu/mcheck/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182627,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183635,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579185034,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579191254,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_smp_cpus_done"
      ]
    },
    {
      "addr": 18446744071579193942,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201375,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579225491,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226369,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579237407,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:crash_load_segments"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259256,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579337768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579397211,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502578,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579516577,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidmap_init",
        "kernel/pid.c:pidmap_init"
      ]
    },
    {
      "addr": 18446744071579580142,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    },
    {
      "addr": 18446744071579593920,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_max_interval",
        "kernel/sched/fair.c:get_update_sysctl_factor"
      ]
    },
    {
      "addr": 18446744071579644777,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579669181,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579684124,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698326,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711485,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596424164,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753550,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579781791,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071579782952,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:printk_safe_flush_on_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827619,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579855766,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579946235,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948506,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579957223,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596434480,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975549,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": [
        "kernel/smp.c:smp_init",
        "kernel/smp.c:smp_init"
      ]
    },
    {
      "addr": 18446744071580105426,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580167619,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:register_kretprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580169557,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199919,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580206203,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580210584,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580321668,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_default_header",
        "kernel/trace/trace.c:print_trace_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580495899,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580533331,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    },
    {
      "addr": 18446744071580536711,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580537979,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541076,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580590098,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580628928,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580633791,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "kernel/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/membarrier.c:SyS_membarrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580716734,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:writeback_set_ratelimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580809909,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071588296771,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830647,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071580862922,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580967076,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596494704,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581114167,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628622,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806502,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:stat_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583475560,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583478763,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583569673,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584091106,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287272,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596645598,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlblk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585343035,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596657108,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586120395,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586380795,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586551198,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586607688,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586613204,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586619565,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596678563,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586723552,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587022854,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587164406,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "net/core/flow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow.c:flow_cache_flush",
        "net/core/flow.c:flow_cache_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587170665,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587359926,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588199709,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:506",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015867,
      "name": "cpumask_weight.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579053504,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579185872,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579201375,
      "name": "cpumask_weight.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579336192,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579491792,
      "name": "cpumask_weight.constprop.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579516577,
      "name": "cpumask_weight.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579550928,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579593920,
      "name": "cpumask_weight.constprop.98",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579781791,
      "name": "cpumask_weight.constprop.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579973920,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580527584,
      "name": "cpumask_weight.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580804208,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580830647,
      "name": "cpumask_weight.constprop.30",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602597210,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994490,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579012097,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013771,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579016411,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579017745,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020905,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065606,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ]
    },
    {
      "addr": 18446744071579072985,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579099251,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579116298,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134658,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151043,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172639,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/cpu/mcheck/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183839,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198067,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199235,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579200698,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579207118,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_smp_cpus_done"
      ]
    },
    {
      "addr": 18446744071579209766,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216844,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579241043,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579241889,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579253871,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:crash_load_segments"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276042,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579363192,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579425272,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529346,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579542655,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579609438,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ]
    },
    {
      "addr": 18446744071579623472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_max_interval",
        "kernel/sched/fair.c:get_update_sysctl_factor"
      ]
    },
    {
      "addr": 18446744071579674166,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579699629,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710763,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730657,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579743189,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579745874,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:SyS_membarrier",
        "kernel/sched/membarrier.c:SyS_membarrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602748979,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786942,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579815230,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071579816328,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:printk_safe_flush_on_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863379,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:irq_create_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896758,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991931,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994202,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003015,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602760368,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022029,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": [
        "kernel/smp.c:smp_init",
        "kernel/smp.c:smp_init"
      ]
    },
    {
      "addr": 18446744071580158082,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:__stop_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580220019,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:register_kretprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580221957,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580253039,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580257563,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580261913,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580374804,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_default_header",
        "kernel/trace/trace.c:print_trace_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580552386,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580597089,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    },
    {
      "addr": 18446744071580601200,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580602411,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605604,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580611736,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580613335,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580670213,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580712207,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_reorder_timer",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580802238,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:writeback_set_ratelimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899525,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071588862030,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580921369,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071580953898,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068740,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602821942,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581225191,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773406,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581956006,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:stat_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583656532,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583659739,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583814985,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362423,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584684634,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584859764,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602975937,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlblk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585771435,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602987337,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586563211,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587018750,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587090789,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587096260,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587102605,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603008499,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587207840,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587520134,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587676009,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587880038,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588748541,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:510",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579016411,
      "name": "cpumask_weight.constprop.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579062288,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579201632,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579216844,
      "name": "cpumask_weight.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579361632,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579518288,
      "name": "cpumask_weight.constprop.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579542655,
      "name": "cpumask_weight.constprop.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579578960,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579623472,
      "name": "cpumask_weight.constprop.100",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579815230,
      "name": "cpumask_weight.constprop.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580020400,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580591088,
      "name": "cpumask_weight.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580892960,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580921369,
      "name": "cpumask_weight.constprop.31",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602765542,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998341,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014723,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579016431,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019127,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579021280,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579023919,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069570,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ]
    },
    {
      "addr": 18446744071579076882,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579104787,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579124217,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144211,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162663,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184005,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/cpu/mcheck/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195689,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209942,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211044,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579212571,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579218506,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_smp_cpus_done"
      ]
    },
    {
      "addr": 18446744071579221652,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228890,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579253570,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:run_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287416,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579375529,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579441142,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579554657,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579570351,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579607904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ]
    },
    {
      "addr": 18446744071579655520,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_max_interval",
        "kernel/sched/fair.c:get_update_sysctl_factor"
      ]
    },
    {
      "addr": 18446744071579710326,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579733734,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579742705,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760478,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776557,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579780242,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_global_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602921371,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579820911,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579848328,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071579849747,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:printk_safe_flush_on_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897552,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579923230,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580043866,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580046330,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580055624,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602934253,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580076100,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": [
        "kernel/smp.c:smp_init",
        "kernel/smp.c:smp_init"
      ]
    },
    {
      "addr": 18446744071580131365,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580217794,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:__stop_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580280243,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:register_kretprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580282261,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313445,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580318001,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580322376,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580436427,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_default_header",
        "kernel/trace/trace.c:print_trace_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580631665,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692536,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580696694,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698005,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580701207,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580720350,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580722647,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580725566,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580801917,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580844337,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_reorder_timer",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580938818,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:writeback_set_ratelimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035333,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071589241101,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057213,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581210260,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265372,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602995370,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373011,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946742,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603017756,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141253,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:stat_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583874511,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583882432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bucket_locks.c:alloc_bucket_spinlocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584021920,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584582918,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584910792,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585090852,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603147329,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlblk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586018616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603158922,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:netif_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586827921,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587317236,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587388888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587394370,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587401506,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603181265,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587508468,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820837,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588005593,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588223077,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589126304,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:512",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019127,
      "name": "cpumask_weight.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579021280,
      "name": "cpumask_weight.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579066768,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579213520,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579228890,
      "name": "cpumask_weight.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579374032,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579544144,
      "name": "cpumask_weight.constprop.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579570351,
      "name": "cpumask_weight.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579607904,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579655520,
      "name": "cpumask_weight.constprop.106",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579848328,
      "name": "cpumask_weight.constprop.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580074480,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581029232,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581057213,
      "name": "cpumask_weight.constprop.29",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604559703,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995941,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579016227,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579017935,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020727,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071604593147,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023120,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579026555,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074194,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ]
    },
    {
      "addr": 18446744071579081602,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579110755,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579130873,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152154,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173365,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185097,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209717,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233574,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234772,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579236251,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579242186,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_smp_cpus_done"
      ]
    },
    {
      "addr": 18446744071579245428,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252587,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579277378,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278192,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:run_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311368,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604667277,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318564,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo",
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    },
    {
      "addr": 18446744071579373364,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd"
      ]
    },
    {
      "addr": 18446744071579403193,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579474646,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579594033,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579607535,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579645024,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ]
    },
    {
      "addr": 18446744071579690752,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_max_interval",
        "kernel/sched/fair.c:get_update_sysctl_factor"
      ]
    },
    {
      "addr": 18446744071579748118,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579773414,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579782638,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803358,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579819261,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823203,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_global_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604719276,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579867615,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579895368,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071579896755,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:printk_safe_flush_on_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944932,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579971838,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580090714,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093162,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580102456,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604732103,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123412,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": [
        "kernel/smp.c:smp_init",
        "kernel/smp.c:smp_init"
      ]
    },
    {
      "addr": 18446744071580178677,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580252070,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580270242,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:__stop_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580332331,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:register_kretprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580334789,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580366021,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580370785,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580375183,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580487147,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:print_trace_header",
        "kernel/trace/trace.c:print_event_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580701832,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580764932,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580769398,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580770661,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580773911,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580779254,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580800478,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580802807,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580805710,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580868477,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913271,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_reorder_timer",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581014786,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:writeback_set_ratelimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112917,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:refresh_zone_stat_thresholds",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071589483408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135034,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581293972,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348548,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604794492,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437035,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582032998,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604816450,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582235877,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:stat_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583966608,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584680287,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585014680,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585201028,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604952001,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlblk_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586157576,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604964423,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:netif_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586984561,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587497468,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587568824,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574338,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587581874,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604990232,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604991485,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587688697,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587966418,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588165689,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588410437,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589360992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/cpumask.c:cpumask_local_spread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579020727,
      "name": "cpumask_weight.constprop.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579023120,
      "name": "cpumask_weight.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579071360,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579237200,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579252587,
      "name": "cpumask_weight.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579318564,
      "name": "cpumask_weight.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579373364,
      "name": "cpumask_weight.constprop.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579401696,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579581392,
      "name": "cpumask_weight.constprop.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579607535,
      "name": "cpumask_weight.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579645024,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579690752,
      "name": "cpumask_weight.constprop.113",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579895368,
      "name": "cpumask_weight.constprop.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580121792,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581106768,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581135034,
      "name": "cpumask_weight.constprop.30",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578882372,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071578987584,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579018992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579024112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself",
        "arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself"
      ]
    },
    {
      "addr": 18446744071579028365,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579029019,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071579030705,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579031200,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579082146,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579087504,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579120704,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579141536,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579159328,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ]
    },
    {
      "addr": 18446744071579185760,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579197552,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:__reload_late",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ]
    },
    {
      "addr": 18446744071579212688,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    },
    {
      "addr": 18446744071579246886,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247248,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579249136,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579250704,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:native_smp_cpus_done",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579257920,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071579266534,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579291682,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292704,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:run_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326558,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    },
    {
      "addr": 18446744071579333027,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071579333790,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579388709,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd",
        "arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd"
      ]
    },
    {
      "addr": 18446744071579417120,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:enable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579484592,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:_cpu_down"
      ]
    },
    {
      "addr": 18446744071579619753,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579631871,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579708821,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    },
    {
      "addr": 18446744071579770661,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_max_interval",
        "kernel/sched/fair.c:get_update_sysctl_factor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579774032,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579784672,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink"
      ]
    },
    {
      "addr": 18446744071579809253,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071579830640,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ]
    },
    {
      "addr": 18446744071579847184,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579850512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_global_expedited"
      ]
    },
    {
      "addr": 18446744071579865671,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071579902096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo"
      ]
    },
    {
      "addr": 18446744071579930154,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071579931507,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:printk_safe_flush_on_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981216,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ]
    },
    {
      "addr": 18446744071580015445,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_scheduler_starting"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited"
      ]
    },
    {
      "addr": 18446744071580131568,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580135072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ]
    },
    {
      "addr": 18446744071580143008,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071580166463,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580167152,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_init",
        "kernel/smp.c:smp_init"
      ]
    },
    {
      "addr": 18446744071580219248,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580286624,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    },
    {
      "addr": 18446744071580318640,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked",
        "kernel/stop_machine.c:__stop_cpus"
      ]
    },
    {
      "addr": 18446744071580377216,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe"
      ]
    },
    {
      "addr": 18446744071580386304,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ]
    },
    {
      "addr": 18446744071580408416,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580421232,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580426800,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    },
    {
      "addr": 18446744071580525072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:print_trace_header",
        "kernel/trace/trace.c:print_event_info"
      ]
    },
    {
      "addr": 18446744071580756704,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071580841792,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    },
    {
      "addr": 18446744071580853424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ]
    },
    {
      "addr": 18446744071580854816,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071580856592,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071580863824,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580888032,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580890352,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580893984,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580935568,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_mmap"
      ]
    },
    {
      "addr": 18446744071581006256,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_reorder_timer",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_do_parallel"
      ]
    },
    {
      "addr": 18446744071581077778,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:writeback_set_ratelimit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581177589,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead",
        "mm/vmstat.c:calculate_normal_threshold",
        "mm/vmstat.c:calculate_pressure_threshold"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:refresh_zone_stat_thresholds"
      ]
    },
    {
      "addr": 18446744071581187525,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071581200570,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581372137,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:set_iounmap_nonlazy"
      ],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    },
    {
      "addr": 18446744071581457664,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    },
    {
      "addr": 18446744071581500358,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071581547168,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:list_locations"
      ]
    },
    {
      "addr": 18446744071582157712,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071582179184,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_create"
      ]
    },
    {
      "addr": 18446744071582216340,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_init"
      ]
    },
    {
      "addr": 18446744071582400293,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:stat_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584146480,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071584292384,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu_counter.c:percpu_counter_cpu_dead"
      ]
    },
    {
      "addr": 18446744071584879696,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    },
    {
      "addr": 18446744071585217696,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    },
    {
      "addr": 18446744071585413312,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071585989738,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071586249964,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlblk_init"
      ]
    },
    {
      "addr": 18446744071586393264,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071586890751,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:netif_init"
      ]
    },
    {
      "addr": 18446744071587243024,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    },
    {
      "addr": 18446744071587769616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587844528,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071587848160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071587854432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    },
    {
      "addr": 18446744071587861601,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071587874299,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071587967872,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071588257840,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071588487376,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071588623728,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071588814224,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    },
    {
      "addr": 18446744071589818048,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:524",
      "file": "lib/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/cpumask.c:cpumask_local_spread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578882372,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071578987584,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579018992,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579024112,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579028365,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579029019,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579030705,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579031200,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579080112,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579087504,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579120704,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579141536,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579159328,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579185760,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579197552,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579212688,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579247248,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579249136,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579250704,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579257920,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579266534,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579326558,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579333027,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579333790,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579388709,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579417120,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579484592,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579605200,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579631871,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579669824,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579774032,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579784672,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579807952,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579830640,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579847184,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579850512,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579865671,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579902096,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579930154,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579981216,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580001520,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580131568,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580135072,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580143008,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580166463,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580167152,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580219248,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580286624,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580318640,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580377216,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580386304,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580408416,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580421232,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580426800,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580525072,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580756704,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580841792,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580853424,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580854816,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580856592,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580863824,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580888032,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580890352,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580893984,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580935568,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581006256,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581171296,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581187525,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581200570,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581365488,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581457664,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581500358,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581547168,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582157712,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582179184,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582216340,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584146480,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584292384,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584879696,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585217696,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585413312,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585989738,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586249964,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586393264,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586890751,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587243024,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587769616,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587844528,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587848160,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587854432,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587861601,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587874299,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587967872,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588257840,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588487376,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588623728,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588814224,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589818048,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578883396,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071578989952,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579021296,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579030627,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579031275,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071579033025,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579033520,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579084162,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579090288,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579143792,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579188048,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579214976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    },
    {
      "addr": 18446744071579252416,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579259568,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071579268187,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579294250,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579297538,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330606,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    },
    {
      "addr": 18446744071579337218,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071579338030,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579420304,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579465184,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_next",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_start"
      ],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_show"
      ]
    },
    {
      "addr": 18446744071579472688,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ]
    },
    {
      "addr": 18446744071579643433,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579657423,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579750949,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    },
    {
      "addr": 18446744071579816912,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579830784,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    },
    {
      "addr": 18446744071579856773,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071579878944,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ]
    },
    {
      "addr": 18446744071579895424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579914295,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071579980298,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071580030880,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ]
    },
    {
      "addr": 18446744071580179808,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580191552,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071580214828,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580215136,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many"
      ]
    },
    {
      "addr": 18446744071580267600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580334960,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    },
    {
      "addr": 18446744071580367472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus"
      ]
    },
    {
      "addr": 18446744071580426032,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe"
      ]
    },
    {
      "addr": 18446744071580457184,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580469984,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580475552,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    },
    {
      "addr": 18446744071580806592,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071580892832,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    },
    {
      "addr": 18446744071580904464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ]
    },
    {
      "addr": 18446744071580905856,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071580907632,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071580914848,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580940704,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580942992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580947280,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581061088,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ]
    },
    {
      "addr": 18446744071581235701,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071581245974,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071581259034,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581564870,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071582234944,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071584269136,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071585554032,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071586136714,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071586539728,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071587974064,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588049360,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071588052976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071588066385,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071588079824,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071588175008,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071588471488,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071588695056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071588845856,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071589037536,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578883396,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071578989952,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579021296,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579030627,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579031275,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579033025,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579033520,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579082112,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579090288,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579143792,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579188048,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579214976,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579252416,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579259568,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579268187,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579294250,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579330606,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579337218,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579338030,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579420304,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579457744,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579472688,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579630928,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579657423,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579706896,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579816912,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579830784,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579855472,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579878944,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579895424,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579914295,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579980298,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580030880,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580179808,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580191552,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580214828,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580215136,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580267600,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580334960,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580367472,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580426032,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580457184,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580469984,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580475552,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580806592,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580892832,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580904464,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580905856,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580907632,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580914848,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580940704,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580942992,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580947280,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581061088,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581233184,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581245974,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581259034,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581564870,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582234944,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584269136,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585554032,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586136714,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586539728,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587974064,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588049360,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588052976,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588066385,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588079824,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588175008,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588471488,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588695056,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588845856,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589037536,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578887913,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071578999840,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579028976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579039123,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579039771,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071579042187,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579042912,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579093264,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579102048,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579160432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579208528,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579236160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ]
    },
    {
      "addr": 18446744071579277472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579286512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071579295855,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579324143,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579327408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ]
    },
    {
      "addr": 18446744071579359931,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_select_clockevents"
      ]
    },
    {
      "addr": 18446744071579366708,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071579367727,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579450432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579477392,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:make_per_cpu_thp",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_show",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_show",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_next",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_start"
      ]
    },
    {
      "addr": 18446744071579494976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ]
    },
    {
      "addr": 18446744071579659872,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579689999,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579747616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ]
    },
    {
      "addr": 18446744071579799632,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_numa_stats"
      ]
    },
    {
      "addr": 18446744071579857392,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:do_balance_runtime"
      ]
    },
    {
      "addr": 18446744071579868512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    },
    {
      "addr": 18446744071579895552,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sd_init",
        "kernel/sched/topology.c:init_sched_groups_capacity",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:init_overlap_sched_group",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:update_top_cache_domain",
        "kernel/sched/topology.c:build_perf_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071579917520,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ]
    },
    {
      "addr": 18446744071579938000,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ]
    },
    {
      "addr": 18446744071579958818,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071580027834,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071580081600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ]
    },
    {
      "addr": 18446744071580090768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp"
      ]
    },
    {
      "addr": 18446744071580244944,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580256560,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071580282569,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580282880,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many_cond"
      ]
    },
    {
      "addr": 18446744071580336848,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580407376,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ]
    },
    {
      "addr": 18446744071580440928,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked"
      ]
    },
    {
      "addr": 18446744071580505920,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe"
      ]
    },
    {
      "addr": 18446744071580539264,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_pid"
      ]
    },
    {
      "addr": 18446744071580554384,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580559856,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack"
      ]
    },
    {
      "addr": 18446744071580927040,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:bpf_map_value_size"
      ]
    },
    {
      "addr": 18446744071581037696,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    },
    {
      "addr": 18446744071581050080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ]
    },
    {
      "addr": 18446744071581052528,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071581054096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071581060864,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581242352,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_init"
      ]
    },
    {
      "addr": 18446744071581419680,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ]
    },
    {
      "addr": 18446744071581435164,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071581448362,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581775468,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071582470576,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071584677056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071586272624,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071586892154,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071587323584,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071588828576,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588910256,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071588913392,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071588927473,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071588941209,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071589039952,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071589333056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071589558208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071589728432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071589998336,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:561",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578887913,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071578999840,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579028976,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579039123,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579039771,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579042187,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579042912,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579093264,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579102048,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579160432,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579208528,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579236160,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579277472,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579286512,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579295855,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579324143,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579327408,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579359931,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579366708,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579367727,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579450432,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579477392,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579494976,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579659872,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579689999,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579747616,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579799632,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579857392,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579868512,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579895552,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579917520,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579938000,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579958818,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580027834,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580081600,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580090768,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580244944,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580256560,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580282569,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580282880,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580336848,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580407376,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580440928,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580505920,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580539264,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580554384,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580559856,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580927040,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581037696,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581050080,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581052528,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581054096,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581060864,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581242352,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581419680,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581435164,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581448362,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581775468,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582470576,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584677056,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586272624,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586892154,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587323584,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588828576,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588910256,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588913392,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588927473,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588941209,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589039952,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589333056,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589558208,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071589728432,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589998336,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591239742,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071579001664,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579032992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071591243075,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071591243099,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071591243491,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579046352,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579094448,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579102224,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579157456,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579203936,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579228896,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ]
    },
    {
      "addr": 18446744071579284656,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579292880,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071591259607,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071591262548,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579328992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ]
    },
    {
      "addr": 18446744071591264096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_select_clockevents"
      ]
    },
    {
      "addr": 18446744071591264442,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071591264562,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579447696,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579477408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ]
    },
    {
      "addr": 18446744071579639664,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071591280944,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579710208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:cpu_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup"
      ]
    },
    {
      "addr": 18446744071579733312,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:init_idle"
      ]
    },
    {
      "addr": 18446744071579790848,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_numa_stats"
      ]
    },
    {
      "addr": 18446744071579849600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:do_balance_runtime"
      ]
    },
    {
      "addr": 18446744071579861280,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending"
      ]
    },
    {
      "addr": 18446744071579890256,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sd_init",
        "kernel/sched/topology.c:init_sched_groups_capacity",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:init_overlap_sched_group",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:update_top_cache_domain",
        "kernel/sched/topology.c:build_perf_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071579910944,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ]
    },
    {
      "addr": 18446744071579925472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ]
    },
    {
      "addr": 18446744071591291049,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071591301576,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071580064176,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ]
    },
    {
      "addr": 18446744071580073936,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp"
      ]
    },
    {
      "addr": 18446744071580228976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580240192,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071591312810,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580266400,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many_cond"
      ]
    },
    {
      "addr": 18446744071580322064,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580394656,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ]
    },
    {
      "addr": 18446744071580428912,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked"
      ]
    },
    {
      "addr": 18446744071580492800,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580527040,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_pid"
      ]
    },
    {
      "addr": 18446744071580542432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580547904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack"
      ]
    },
    {
      "addr": 18446744071580923968,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:bpf_map_value_size"
      ]
    },
    {
      "addr": 18446744071581041072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/bpf/map_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_iter_attach_map"
      ]
    },
    {
      "addr": 18446744071581046144,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_iter_init_hash_map",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    },
    {
      "addr": 18446744071581061472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:bpf_iter_init_array_map"
      ]
    },
    {
      "addr": 18446744071581064192,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071581066256,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071581072736,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    },
    {
      "addr": 18446744071581137040,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071581284592,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_init"
      ]
    },
    {
      "addr": 18446744071581462768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ]
    },
    {
      "addr": 18446744071581477632,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071581483424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581556688,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap_lock.c:trace_mmap_lock_reg"
      ]
    },
    {
      "addr": 18446744071591332403,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071581874320,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582527584,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071584794672,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071586389824,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071591483479,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071587385424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071588845088,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588922768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071588926032,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071591599986,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071591600010,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071589049280,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071589334096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071589567440,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071590040624,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:567",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591239742,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579001664,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579032992,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071591243075,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591243099,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591243491,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579046352,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579094448,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579102224,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579157456,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579203936,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579228896,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579284656,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579292880,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071591259607,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591262548,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579328992,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591264096,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591264442,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591264562,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579447696,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579477408,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579639664,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591280944,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579710208,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579733312,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579790848,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579849600,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579861280,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579890256,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579910944,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579925472,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071591291049,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591301576,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580064176,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580073936,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580228976,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580240192,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591312810,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580266400,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580322064,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580394656,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580428912,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580492800,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580527040,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580542432,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580547904,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580923968,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581041072,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581046144,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581061472,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581064192,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581066256,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581072736,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581137040,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581284592,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581462768,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581477632,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581483424,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581556688,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591332403,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581874320,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582527584,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584794672,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586389824,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591483479,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587385424,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588845088,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588922768,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588926032,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071591599986,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591600010,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589049280,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589334096,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589567440,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071590040624,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591182542,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071579009600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579035664,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071591186578,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071591186602,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071591187019,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579049264,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579100832,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579108544,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579164432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579206336,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579230976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ]
    },
    {
      "addr": 18446744071579287376,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579295552,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071591202522,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071591205130,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579331696,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ]
    },
    {
      "addr": 18446744071591206415,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_select_clockevents"
      ]
    },
    {
      "addr": 18446744071591206617,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071591206737,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579450256,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579479392,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ]
    },
    {
      "addr": 18446744071579645520,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071591223893,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579717616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:cpu_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup"
      ]
    },
    {
      "addr": 18446744071579739840,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:init_idle"
      ]
    },
    {
      "addr": 18446744071579799216,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_numa_stats"
      ]
    },
    {
      "addr": 18446744071579858000,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579869824,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending"
      ]
    },
    {
      "addr": 18446744071579898848,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sd_init",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:update_top_cache_domain",
        "kernel/sched/topology.c:build_perf_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071579933984,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ]
    },
    {
      "addr": 18446744071591234122,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071591244361,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071580064832,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ]
    },
    {
      "addr": 18446744071580075264,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp"
      ]
    },
    {
      "addr": 18446744071580234016,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580245440,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071591255236,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580325568,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580397600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ]
    },
    {
      "addr": 18446744071580433344,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked"
      ]
    },
    {
      "addr": 18446744071580496592,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580530688,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_pid"
      ]
    },
    {
      "addr": 18446744071580545744,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580551072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack"
      ]
    },
    {
      "addr": 18446744071580927328,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    },
    {
      "addr": 18446744071581054464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/map_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_iter_attach_map"
      ]
    },
    {
      "addr": 18446744071581060992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_iter_init_hash_map",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    },
    {
      "addr": 18446744071581076592,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:bpf_iter_init_array_map"
      ]
    },
    {
      "addr": 18446744071581079312,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071581081088,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071581087728,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    },
    {
      "addr": 18446744071581093424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071581302544,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_init"
      ]
    },
    {
      "addr": 18446744071581483584,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ]
    },
    {
      "addr": 18446744071581498416,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071614432358,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581579504,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap_lock.c:trace_mmap_lock_reg"
      ]
    },
    {
      "addr": 18446744071591275087,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071581904960,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582556368,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071584838816,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071586273808,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071591427014,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071587267552,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071588732160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588811360,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071588814224,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071591543638,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071591543662,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071588936656,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071589047744,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/powercap/dtpm_cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline",
        "drivers/powercap/dtpm_cpu.c:get_pd_power_uw",
        "drivers/powercap/dtpm_cpu.c:set_pd_power_limit"
      ]
    },
    {
      "addr": 18446744071589229600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071589466000,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071589954832,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591182542,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579009600,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579035664,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071591186578,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591186602,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591187019,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579049264,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579100832,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579108544,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579164432,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579206336,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579230976,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579287376,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579295552,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071591202522,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591205130,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579331696,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591206415,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591206617,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591206737,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579450256,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579479392,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579645520,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591223893,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579717616,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579739840,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579799216,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579858000,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579869824,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579898848,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579933984,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071591234122,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591244361,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580064832,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580075264,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580234016,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580245440,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591255236,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580325568,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580397600,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580433344,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580496592,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580530688,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580545744,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580551072,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580927328,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581054464,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581060992,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581076592,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581079312,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581081088,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581087728,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581093424,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581302544,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581483584,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581498416,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581502944,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581579504,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591275087,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581904960,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582556368,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584838816,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586273808,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591427014,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587267552,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588732160,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588811360,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588814224,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071591543638,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591543662,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588936656,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589047744,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071589229600,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589466000,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071589954832,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592039585,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071579027616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579054208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071592049633,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071592049657,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071592050089,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579070128,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579077248,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    },
    {
      "addr": 18446744071579124752,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579132720,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579195152,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579242896,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579269888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ]
    },
    {
      "addr": 18446744071579331376,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579342688,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071592073518,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071592076882,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579386960,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ]
    },
    {
      "addr": 18446744071592078716,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_select_clockevents"
      ]
    },
    {
      "addr": 18446744071592079464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:pv_ipi_supported",
        "arch/x86/kernel/kvm.c:pv_tlb_flush_supported",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071592079820,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579514768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579545664,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ]
    },
    {
      "addr": 18446744071579722224,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071592105176,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579795904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:cpu_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup"
      ]
    },
    {
      "addr": 18446744071579820176,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:sched_core_cpu_starting"
      ]
    },
    {
      "addr": 18446744071579895248,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_numa_stats"
      ]
    },
    {
      "addr": 18446744071579965888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579980016,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:task_non_contending"
      ]
    },
    {
      "addr": 18446744071580014048,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:sd_init",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:update_top_cache_domain",
        "kernel/sched/topology.c:build_perf_domains",
        "kernel/sched/topology.c:sched_domain_debug_one"
      ]
    },
    {
      "addr": 18446744071580057776,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ]
    },
    {
      "addr": 18446744071592121921,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071592132999,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071580198256,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ]
    },
    {
      "addr": 18446744071580209664,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp"
      ]
    },
    {
      "addr": 18446744071580338976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580382960,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580396112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071592157966,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580480096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580560272,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ]
    },
    {
      "addr": 18446744071580597280,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_cpuslocked"
      ]
    },
    {
      "addr": 18446744071580664192,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580702560,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_pid"
      ]
    },
    {
      "addr": 18446744071580717280,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580720832,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack"
      ]
    },
    {
      "addr": 18446744071581130384,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581279488,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/map_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_iter_attach_map"
      ]
    },
    {
      "addr": 18446744071581286144,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_iter_init_hash_map",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    },
    {
      "addr": 18446744071581304368,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:bpf_iter_init_array_map"
      ]
    },
    {
      "addr": 18446744071581307152,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071581309152,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071581316640,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    },
    {
      "addr": 18446744071581322608,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071581547136,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_init"
      ]
    },
    {
      "addr": 18446744071581739616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ]
    },
    {
      "addr": 18446744071581758416,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071615372639,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581844448,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap_lock.c:trace_mmap_lock_reg"
      ]
    },
    {
      "addr": 18446744071581996320,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    },
    {
      "addr": 18446744071592210956,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071582199968,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582872544,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071585258192,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071586786080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071592485183,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071587834800,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071589422160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589504208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071589507152,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071592659178,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071592659347,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071589644400,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071592685250,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/hv_common.c:hv_common_init",
        "drivers/hv/hv_common.c:hv_common_init"
      ]
    },
    {
      "addr": 18446744071589764800,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "drivers/powercap/dtpm_cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline",
        "drivers/powercap/dtpm_cpu.c:get_pd_power_uw",
        "drivers/powercap/dtpm_cpu.c:set_pd_power_limit"
      ]
    },
    {
      "addr": 18446744071589953040,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071590204432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071590722016,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:538",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592039585,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579027616,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579054208,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071592049633,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592049657,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592050089,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579070128,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579077248,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579124752,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579132720,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579195152,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579242896,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579269888,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579331376,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579342688,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071592073518,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592076882,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579386960,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592078716,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592079464,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592079820,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579514768,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579545664,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579722224,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592105176,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579795904,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579820176,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579895248,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579965888,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579980016,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580014048,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580057776,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071592121921,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592132999,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580198256,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580209664,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580338976,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580382960,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580396112,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592157966,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580480096,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580560272,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580597280,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580664192,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580702560,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580717280,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580720832,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581130384,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581279488,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581286144,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581304368,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581307152,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581309152,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581316640,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581322608,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581547136,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581739616,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581758416,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581763712,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581844448,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581996320,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071592210956,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582199968,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582872544,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585258192,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586786080,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592485183,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587834800,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589422160,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589504208,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071589507152,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071592659178,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592659347,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589644400,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071592685250,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589764800,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071589953040,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071590204432,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071590722016,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593805613,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071579048096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579081632,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071593816023,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071593816075,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071593816546,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579094928,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579105024,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    },
    {
      "addr": 18446744071579158272,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579168672,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:unsynchronized_tsc"
      ]
    },
    {
      "addr": 18446744071579244304,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579294528,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579392464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579403488,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071593840110,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071593843378,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579452960,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ]
    },
    {
      "addr": 18446744071593845186,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_select_clockevents"
      ]
    },
    {
      "addr": 18446744071593846698,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:pv_ipi_supported",
        "arch/x86/kernel/kvm.c:pv_tlb_flush_supported",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071593847074,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579634256,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ]
    },
    {
      "addr": 18446744071579826896,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071593872812,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579903488,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:cpu_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup"
      ]
    },
    {
      "addr": 18446744071579937008,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:sched_core_cpu_starting"
      ]
    },
    {
      "addr": 18446744071580006352,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_numa_stats"
      ]
    },
    {
      "addr": 18446744071580082528,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:task_non_contending"
      ]
    },
    {
      "addr": 18446744071580142512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:update_top_cache_domain",
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/sched/build_utility.c:sugov_start"
      ]
    },
    {
      "addr": 18446744071593891380,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071580263104,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    },
    {
      "addr": 18446744071593903701,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071580351344,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ]
    },
    {
      "addr": 18446744071580368400,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580600208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580615424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071593932986,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580674512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580760272,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ]
    },
    {
      "addr": 18446744071580799984,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked"
      ]
    },
    {
      "addr": 18446744071580875232,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580914944,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_pid"
      ]
    },
    {
      "addr": 18446744071580929024,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580932848,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack"
      ]
    },
    {
      "addr": 18446744071581370304,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/trace/fprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fprobe.c:fprobe_init_rethook"
      ]
    },
    {
      "addr": 18446744071581400992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581573904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/bpf/map_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_iter_attach_map"
      ]
    },
    {
      "addr": 18446744071581582496,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_iter_init_hash_map",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_free_timers",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    },
    {
      "addr": 18446744071581602832,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:bpf_iter_init_array_map"
      ]
    },
    {
      "addr": 18446744071581605936,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071581608112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071581618208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    },
    {
      "addr": 18446744071581625888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071581898928,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_init"
      ]
    },
    {
      "addr": 18446744071582140192,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071617160671,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071582237776,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap_lock.c:trace_mmap_lock_reg"
      ]
    },
    {
      "addr": 18446744071582420320,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    },
    {
      "addr": 18446744071593989399,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071582664928,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:calculate_sizes"
      ]
    },
    {
      "addr": 18446744071583436768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071584422480,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "fs/squashfs/decompressor_multi_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors"
      ]
    },
    {
      "addr": 18446744071586100880,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071588066320,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071594354182,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071589187184,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071590716848,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn"
      ]
    },
    {
      "addr": 18446744071590901776,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590987760,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071590990992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071594544121,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071594544319,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071591145472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071594570499,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/hv_common.c:hv_common_init",
        "drivers/hv/hv_common.c:hv_common_init"
      ]
    },
    {
      "addr": 18446744071591491040,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071591778176,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071592351024,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:573",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593805613,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579048096,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579081632,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593816023,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593816075,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593816546,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579094928,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579105024,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579158272,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579168672,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579244304,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579294528,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579392464,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579403488,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593840110,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593843378,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579452960,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593845186,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593846698,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593847074,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579634256,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579826896,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593872812,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579903488,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579937008,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580006352,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580082528,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580142512,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593891380,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580263104,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593903701,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580351344,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580368400,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580600208,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580615424,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593932986,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580674512,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580760272,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580799984,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580875232,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580914944,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580929024,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580932848,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581370304,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581400992,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581573904,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581582496,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581602832,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581605936,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581608112,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581618208,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581625888,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581898928,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582140192,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582147152,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582237776,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582420320,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593989399,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582664928,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583436768,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584422480,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586100880,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588066320,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071594354182,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589187184,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590716848,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590901776,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590987760,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590990992,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071594544121,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071594544319,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591145472,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071594570499,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591491040,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591778176,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071592351024,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578894256,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071579078336,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579114656,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579122336,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579125792,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071579127120,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579131008,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579142304,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    },
    {
      "addr": 18446744071579208112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579221840,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:unsynchronized_tsc"
      ]
    },
    {
      "addr": 18446744071579304288,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579360736,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579470752,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579484080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071579488384,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579534064,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579541472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ]
    },
    {
      "addr": 18446744071579584672,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_select_clockevents"
      ]
    },
    {
      "addr": 18446744071579591888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask",
        "arch/x86/kernel/kvm.c:pv_tlb_flush_supported",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071579597856,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579749376,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ]
    },
    {
      "addr": 18446744071579964416,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579994080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071580055888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:cpu_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup"
      ]
    },
    {
      "addr": 18446744071580087712,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_core_cpu_deactivate",
        "kernel/sched/core.c:sched_core_cpu_starting"
      ]
    },
    {
      "addr": 18446744071580168928,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_numa_stats"
      ]
    },
    {
      "addr": 18446744071580254320,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:dl_cpu_busy",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:task_non_contending"
      ]
    },
    {
      "addr": 18446744071580317056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:update_top_cache_domain",
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/sched/build_utility.c:sugov_start"
      ]
    },
    {
      "addr": 18446744071580410560,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071580468720,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    },
    {
      "addr": 18446744071580478704,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071580573584,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:alloc_nodes_vectors"
      ]
    },
    {
      "addr": 18446744071580589632,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp"
      ]
    },
    {
      "addr": 18446744071580696944,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_init_late",
        "kernel/dma/swiotlb.c:swiotlb_init_remap"
      ]
    },
    {
      "addr": 18446744071580863440,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580880320,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071580889232,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580945184,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071581038112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ]
    },
    {
      "addr": 18446744071581085200,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked"
      ]
    },
    {
      "addr": 18446744071581164576,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581207056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_pid"
      ]
    },
    {
      "addr": 18446744071581221168,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581225728,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack"
      ]
    },
    {
      "addr": 18446744071581706608,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/trace/fprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fprobe.c:fprobe_init_rethook"
      ]
    },
    {
      "addr": 18446744071581751840,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581950704,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/bpf/map_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_iter_attach_map"
      ]
    },
    {
      "addr": 18446744071581960576,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_iter_init_hash_map",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    },
    {
      "addr": 18446744071581983248,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:bpf_iter_init_array_map"
      ]
    },
    {
      "addr": 18446744071581988672,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071581991840,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071582002672,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    },
    {
      "addr": 18446744071582013280,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071582332592,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_init"
      ]
    },
    {
      "addr": 18446744071582617728,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch_init",
        "mm/mm_init.c:mm_compute_batch_notifier"
      ]
    },
    {
      "addr": 18446744071627846279,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071582728112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap_lock.c:trace_mmap_lock_reg"
      ]
    },
    {
      "addr": 18446744071582928128,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    },
    {
      "addr": 18446744071583066368,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071583190160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:calculate_sizes"
      ]
    },
    {
      "addr": 18446744071584026464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071585083168,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "fs/squashfs/decompressor_multi_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors"
      ]
    },
    {
      "addr": 18446744071587085760,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071589447408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071589931680,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:try_to_generate_entropy"
      ]
    },
    {
      "addr": 18446744071590221696,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071590741408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071592388528,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn"
      ]
    },
    {
      "addr": 18446744071592595712,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592692528,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071592697168,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071592719360,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071592727200,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071592871552,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071592988992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/hv_common.c:hv_common_init",
        "drivers/hv/hv_common.c:hv_common_init"
      ]
    },
    {
      "addr": 18446744071593260000,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071593570864,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071594190288,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:638",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894256,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579078336,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579114656,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579122336,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579125792,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579127120,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579131008,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579142304,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579208112,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579221840,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579304288,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579360736,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579470752,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579484080,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579488384,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579534064,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579541472,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579584672,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579591888,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579597856,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579749376,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579964416,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579994080,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580055888,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580087712,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580168928,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580254320,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580317056,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580410560,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580468720,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580478704,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580573584,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580589632,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580696944,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580863440,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580880320,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580889232,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580945184,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581038112,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581085200,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581164576,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581207056,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581221168,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581225728,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581706608,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581751840,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581950704,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581960576,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581983248,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581988672,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581991840,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582002672,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582013280,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582332592,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582617728,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582625776,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582728112,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582928128,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583066368,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583190160,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584026464,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585083168,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587085760,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589447408,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589931680,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590221696,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590741408,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071592388528,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071592595712,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071592692528,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071592697168,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071592719360,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071592727200,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071592871552,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071592988992,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593260000,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593570864,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071594190288,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578892112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071579078128,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579114976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579122624,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579126112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071579127440,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579131440,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579142992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    },
    {
      "addr": 18446744071579212400,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579227904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:unsynchronized_tsc"
      ]
    },
    {
      "addr": 18446744071579311472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579369920,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579483760,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579496208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071579500576,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579546976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579554720,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ]
    },
    {
      "addr": 18446744071579597168,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_select_clockevents"
      ]
    },
    {
      "addr": 18446744071579604432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask",
        "arch/x86/kernel/kvm.c:pv_tlb_flush_supported",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071579610640,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579795936,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ]
    },
    {
      "addr": 18446744071580014560,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071580047904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071580110320,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:cpu_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup"
      ]
    },
    {
      "addr": 18446744071580143648,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:task_mm_cid_work",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_core_cpu_deactivate",
        "kernel/sched/core.c:sched_core_cpu_starting"
      ]
    },
    {
      "addr": 18446744071580234432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_numa_stats"
      ]
    },
    {
      "addr": 18446744071580320112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:task_non_contending"
      ]
    },
    {
      "addr": 18446744071580383856,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:update_top_cache_domain",
        "kernel/sched/build_utility.c:build_perf_domains",
        "kernel/sched/build_utility.c:sugov_start"
      ]
    },
    {
      "addr": 18446744071580479328,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071580540176,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    },
    {
      "addr": 18446744071580550240,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071580648192,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors"
      ]
    },
    {
      "addr": 18446744071580663088,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp"
      ]
    },
    {
      "addr": 18446744071580773648,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_init_late",
        "kernel/dma/swiotlb.c:swiotlb_init_remap"
      ]
    },
    {
      "addr": 18446744071580947200,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580964848,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071580973072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:futex_init"
      ]
    },
    {
      "addr": 18446744071581032240,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071581126480,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ]
    },
    {
      "addr": 18446744071581177056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked"
      ]
    },
    {
      "addr": 18446744071581258304,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581301408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_pid"
      ]
    },
    {
      "addr": 18446744071581315600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581320080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack"
      ]
    },
    {
      "addr": 18446744071581852320,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/trace/fprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fprobe.c:fprobe_init_rethook"
      ]
    },
    {
      "addr": 18446744071581911856,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582138784,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/bpf/map_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_iter_attach_map"
      ]
    },
    {
      "addr": 18446744071582149040,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "kernel/bpf/hashtab.c:bpf_iter_init_hash_map",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    },
    {
      "addr": 18446744071582174752,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_mem_usage",
        "kernel/bpf/arraymap.c:bpf_iter_init_array_map"
      ]
    },
    {
      "addr": 18446744071582180000,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071582183168,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071582193808,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    },
    {
      "addr": 18446744071582204096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071582533808,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_init"
      ]
    },
    {
      "addr": 18446744071582826464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch_init",
        "mm/mm_init.c:mm_compute_batch_notifier"
      ]
    },
    {
      "addr": 18446744071619623122,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071582943520,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap_lock.c:trace_mmap_lock_reg"
      ]
    },
    {
      "addr": 18446744071583107920,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_ram_vread_iter",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:free_vmap_block"
      ]
    },
    {
      "addr": 18446744071583144000,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    },
    {
      "addr": 18446744071583276880,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071583407920,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:calculate_sizes"
      ]
    },
    {
      "addr": 18446744071584252608,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071585312784,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "fs/squashfs/decompressor_multi_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors"
      ]
    },
    {
      "addr": 18446744071587344768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071588178384,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "lib/group_cpus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:alloc_nodes_groups"
      ]
    },
    {
      "addr": 18446744071589746864,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071590241056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:try_to_generate_entropy"
      ]
    },
    {
      "addr": 18446744071590541568,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071591082768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071592817600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn"
      ]
    },
    {
      "addr": 18446744071593026288,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593123488,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071593128128,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071593156352,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    },
    {
      "addr": 18446744071593164336,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071593310016,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071593440560,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/hv_common.c:hv_common_init",
        "drivers/hv/hv_common.c:hv_common_init"
      ]
    },
    {
      "addr": 18446744071593717904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071594042848,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask"
      ]
    },
    {
      "addr": 18446744071594577392,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:690",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578892112,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579078128,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579114976,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579122624,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579126112,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579127440,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579131440,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579142992,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579212400,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579227904,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579311472,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579369920,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579483760,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579496208,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579500576,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579546976,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579554720,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579597168,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579604432,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579610640,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579795936,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580014560,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580047904,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580110320,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580143648,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580234432,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580320112,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580383856,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580479328,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580540176,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580550240,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580648192,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580663088,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580773648,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580947200,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580964848,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580973072,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581032240,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581126480,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581177056,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581258304,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581301408,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581315600,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581320080,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581852320,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581911856,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582138784,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582149040,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582174752,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582180000,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582183168,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582193808,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582204096,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582533808,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582826464,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582834864,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582943520,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583107920,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583144000,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583276880,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583407920,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584252608,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585312784,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587344768,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588178384,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589746864,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590241056,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590541568,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591082768,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071592817600,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593026288,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593123488,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593128128,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593156352,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593164336,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593310016,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593440560,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593717904,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071594042848,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071594577392,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578914512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071579103904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579140784,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579148480,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579152016,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071579153648,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579157760,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi"
      ]
    },
    {
      "addr": 18446744071579171792,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ]
    },
    {
      "addr": 18446744071579241440,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579256768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:unsynchronized_tsc"
      ]
    },
    {
      "addr": 18446744071579342224,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579401424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579513968,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:remove_siblinginfo",
        "arch/x86/kernel/smpboot.c:announce_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579526032,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071579530896,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579575248,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579582240,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ]
    },
    {
      "addr": 18446744071579626928,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_select_clockevents"
      ]
    },
    {
      "addr": 18446744071579634160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_alloc_cpumask",
        "arch/x86/kernel/kvm.c:pv_tlb_flush_supported",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071579640400,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579829104,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ]
    },
    {
      "addr": 18446744071580090400,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071580155360,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:cpu_store",
        "kernel/reboot.c:reboot_setup",
        "kernel/reboot.c:reboot_setup"
      ]
    },
    {
      "addr": 18446744071580189072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:task_mm_cid_work",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_core_cpu_deactivate",
        "kernel/sched/core.c:sched_core_cpu_starting"
      ]
    },
    {
      "addr": 18446744071580282272,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:update_numa_stats"
      ]
    },
    {
      "addr": 18446744071580372800,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:dl_bw_manage",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:sched_dl_global_validate",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:set_cpus_allowed_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:task_non_contending"
      ]
    },
    {
      "addr": 18446744071580440464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:build_sched_domains",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sd_init",
        "kernel/sched/build_utility.c:init_sched_groups_capacity",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:update_top_cache_domain",
        "kernel/sched/build_utility.c:sugov_start"
      ]
    },
    {
      "addr": 18446744071580539152,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071580601984,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    },
    {
      "addr": 18446744071580611712,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071580713408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors"
      ]
    },
    {
      "addr": 18446744071580729808,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp"
      ]
    },
    {
      "addr": 18446744071580860096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_init_late",
        "kernel/dma/swiotlb.c:swiotlb_init_remap"
      ]
    },
    {
      "addr": 18446744071581038496,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071581056176,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071581067808,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:futex_init"
      ]
    },
    {
      "addr": 18446744071581115616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/crash_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071581282736,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_core_cpuslocked",
        "kernel/stop_machine.c:stop_machine_cpuslocked"
      ]
    },
    {
      "addr": 18446744071581364544,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581407632,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_pid"
      ]
    },
    {
      "addr": 18446744071581421792,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581426384,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_show_stack"
      ]
    },
    {
      "addr": 18446744071581754496,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    },
    {
      "addr": 18446744071581975648,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/trace/fprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fprobe.c:fprobe_init_rethook"
      ]
    },
    {
      "addr": 18446744071582036704,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582286192,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/bpf/map_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/map_iter.c:bpf_iter_attach_map"
      ]
    },
    {
      "addr": 18446744071582298112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "kernel/bpf/hashtab.c:bpf_iter_init_hash_map",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init"
      ]
    },
    {
      "addr": 18446744071582323072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_mem_usage",
        "kernel/bpf/arraymap.c:bpf_iter_init_array_map"
      ]
    },
    {
      "addr": 18446744071582328768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071582331936,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071582342704,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    },
    {
      "addr": 18446744071582353328,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071582540384,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/bpf/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumask.c:bpf_cpumask_weight"
      ]
    },
    {
      "addr": 18446744071582702784,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_init"
      ]
    },
    {
      "addr": 18446744071583000912,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch_init",
        "mm/mm_init.c:mm_compute_batch_notifier"
      ]
    },
    {
      "addr": 18446744071621927266,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_build_alloc_info"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071583118736,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap_lock.c:trace_mmap_lock_reg"
      ]
    },
    {
      "addr": 18446744071583290544,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_ram_vread_iter",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:free_vmap_block"
      ]
    },
    {
      "addr": 18446744071583327616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:zone_set_pageset_high_and_batch",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch",
        "mm/page_alloc.c:zone_set_pageset_high_and_batch"
      ]
    },
    {
      "addr": 18446744071583387648,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:calculate_sizes"
      ]
    },
    {
      "addr": 18446744071583513024,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071584469824,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071585547232,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "fs/squashfs/decompressor_multi_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors"
      ]
    },
    {
      "addr": 18446744071587628224,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071588469232,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "lib/group_cpus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/group_cpus.c:__group_cpus_evenly",
        "lib/group_cpus.c:alloc_nodes_groups"
      ]
    },
    {
      "addr": 18446744071590084880,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071590582080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:try_to_generate_entropy"
      ]
    },
    {
      "addr": 18446744071590897600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071591022592,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/cacheinfo.c:update_per_cpu_data_slice_size"
      ]
    },
    {
      "addr": 18446744071591427664,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071593566464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_offline",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn"
      ]
    },
    {
      "addr": 18446744071593777712,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593876512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071593881296,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071593910160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe"
      ]
    },
    {
      "addr": 18446744071593917280,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071594066560,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071594186448,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/hv_common.c:hv_common_init",
        "drivers/hv/hv_common.c:hv_common_init"
      ]
    },
    {
      "addr": 18446744071594499344,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071594833136,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask"
      ]
    },
    {
      "addr": 18446744071595381072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    },
    {
      "addr": 18446744071595936656,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "net/ipv4/tcp_sigpool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch"
      ]
    },
    {
      "addr": 18446744071597267008,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:704",
      "file": "lib/objpool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/objpool.c:objpool_pop",
        "lib/objpool.c:objpool_init_percpu_slots",
        "lib/objpool.c:objpool_init_percpu_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578914512,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579103904,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579140784,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579148480,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579152016,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579153648,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579157760,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579171792,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579241440,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579256768,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579342224,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579401424,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579513968,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579526032,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579530896,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579575248,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579582240,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579626928,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579634160,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579640400,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579829104,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580090400,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580155360,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580189072,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580282272,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580372800,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580440464,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580539152,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580601984,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580611712,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580713408,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580729808,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580860096,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581038496,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581056176,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581067808,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581115616,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581282736,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581364544,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581407632,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581421792,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581426384,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071581754496,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581975648,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582036704,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582286192,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582298112,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582323072,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582328768,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582331936,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582342704,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582353328,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582540384,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582702784,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583000912,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583009312,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583118736,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583290544,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583327616,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583387648,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583513024,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584469824,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585547232,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587628224,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588469232,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590084880,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590582080,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590897600,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591022592,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591427664,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593566464,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593777712,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593876512,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593881296,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593910160,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593917280,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071594066560,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071594186448,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071594499344,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071594833136,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595381072,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071595936656,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071597267008,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510817728,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/arm64/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490276016,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:cpus_are_stuck_in_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490350864,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/arm64/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/context.c:asids_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490794040,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510879296,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490931176,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491005168,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491038696,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491056408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491081268,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491093776,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510890196,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491238644,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491406428,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491424880,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510903488,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491455336,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491513072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491613424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491633912,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491701288,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491740332,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491747288,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491751824,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492136064,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492218836,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492233732,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492236608,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492241224,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492246896,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492280064,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492285208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492289556,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492425480,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510944400,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503916832,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492663004,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_embed_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510971248,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493820556,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496153288,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496365300,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496411108,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496428404,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/irqchip/irq-ls-scfg-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497125600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/pci/controller/pci-xgene-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497127532,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/pci/controller/pcie-iproc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498053220,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498115440,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq",
        "drivers/soc/fsl/qbman/qman.c:qman_enable_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498215508,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511225884,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:topology_parse_cpu_capacity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499429240,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500986368,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501019528,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/thermal/cpu_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:cpufreq_state2power",
        "drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501219720,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501319084,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501473812,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501777544,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu.c:armpmu_request_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501995568,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502255604,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502415368,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502646936,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243265536,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/arm/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 3243269288,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3224457676,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/arm/kernel/machine_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/machine_kexec.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3224554484,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/arm/mach-exynos/exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion"
      ],
      "caller_func": []
    },
    {
      "addr": 3243304328,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/arm/mach-mvebu/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_init_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3224835856,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 3224862100,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 3224949120,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3225008340,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225048492,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 3225061180,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": []
    },
    {
      "addr": 3225085436,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3225097568,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3225191844,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 3225251408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225403008,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3225418860,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3243390596,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225441572,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 3225569472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 3225587064,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3225654996,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225689300,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225695424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225699952,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 3226025076,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226118840,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226129600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226131688,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 3226135320,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 3226141056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226169228,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3226172144,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226176768,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226304976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 3226476296,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 3243435168,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3226501504,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_dump_alloc_info"
      ]
    },
    {
      "addr": 3227322732,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3229473808,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3229700796,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gic_get_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 3230815000,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe"
      ]
    },
    {
      "addr": 3230903624,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/soc/tegra/flowctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/flowctrl.c:flowctrl_cpu_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3243871524,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:topology_parse_cpu_capacity"
      ],
      "caller_func": []
    },
    {
      "addr": 3233503212,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3233532128,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/thermal/cpu_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:cpufreq_state2power",
        "drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3233723096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233805708,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3233829000,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpuidle/coupled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/coupled.c:coupled_cpu_online",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3234022628,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3234327300,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu.c:armpmu_request_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3234768696,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3235002236,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3235153204,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235351812,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224835712,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3224862100,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3225056780,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 3225191844,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3226474540,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3226501504,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3230815000,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302390948,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/kernel/setup-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282388344,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/watchdog.c:start_watchdog",
        "arch/powerpc/kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282624540,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282832356,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302451628,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/sysdev/mpic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/mpic.c:smp_mpic_probe",
        "arch/powerpc/sysdev/mpic.c:mpic_alloc",
        "arch/powerpc/sysdev/mpic.c:mpic_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282937332,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/sysdev/xive/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283079904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/platforms/powernv/opal-imc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283125128,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/platforms/pseries/lpar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302488756,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/platforms/pseries/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283183260,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/platforms/pseries/hotplug-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283275424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/xmon/xmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/xmon/xmon.c:symbol_lookup",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:wait_for_other_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283396444,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/powerpc/perf/imc-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "arch/powerpc/perf/imc-pmu.c:cleanup_all_core_imc_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283620880,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active",
        "kernel/workqueue.c:workqueue_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302510312,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283786160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283873708,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283917724,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283934400,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283966096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283982424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302524276,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284139376,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284352344,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284373072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302538960,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284406076,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284478884,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284600620,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:update_cpumask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284627676,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284722496,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284772680,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284781992,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284790052,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285332888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285443104,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285460040,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285462960,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285468112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285476736,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285513984,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285518644,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285524800,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285686924,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302592700,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297810972,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285982848,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_embed_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302625836,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287440608,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290414456,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292674916,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294455176,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294502720,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/thermal/cpu_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:cpufreq_state2power",
        "drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294745208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294854336,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302842208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/powernv-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295009912,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295457324,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295756224,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295971956,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296247348,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271479044,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446743936271502708,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446743936271566072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271612688,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:do_balance_runtime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271639912,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271650442,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271670226,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271718874,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446743936271768458,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271882340,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_register_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271892022,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270641450,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271911408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272015786,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272030756,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272294692,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272368554,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272380522,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272382352,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272385576,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272391072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272416166,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_init_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272418780,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272422710,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272510956,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270673800,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270674592,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272672598,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_dump_alloc_info"
      ]
    },
    {
      "addr": 18446743936270696770,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273398352,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275206336,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270773202,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/irqchip/irq-sifive-plic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-sifive-plic.c:plic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270800856,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:topology_parse_cpu_capacity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276655766,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277915710,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278061558,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278308900,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278499436,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278624534,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278788194,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271477698,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446743936271502708,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446743936271647640,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446743936271718874,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446743936272672598,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578883396,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071578990304,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579021648,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579030979,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579031627,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071579033377,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579033872,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579084514,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579090640,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579144160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579186896,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579213824,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    },
    {
      "addr": 18446744071579251120,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579258272,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071579266891,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579293346,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326510,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    },
    {
      "addr": 18446744071579333122,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071579333934,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579416144,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579619737,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579633743,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579726869,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    },
    {
      "addr": 18446744071579792512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579803136,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    },
    {
      "addr": 18446744071579829125,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071579851088,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ]
    },
    {
      "addr": 18446744071579867536,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579886407,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071579949034,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071579999616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ]
    },
    {
      "addr": 18446744071580149008,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580160352,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071580183628,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580183936,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many"
      ]
    },
    {
      "addr": 18446744071580236400,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580303760,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    },
    {
      "addr": 18446744071580336272,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus"
      ]
    },
    {
      "addr": 18446744071580394832,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe"
      ]
    },
    {
      "addr": 18446744071580425984,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580438784,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580444352,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    },
    {
      "addr": 18446744071580775392,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071580861632,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    },
    {
      "addr": 18446744071580873264,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ]
    },
    {
      "addr": 18446744071580874656,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071580876432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071580883648,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580909504,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580911792,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580916080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581029936,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ]
    },
    {
      "addr": 18446744071581204549,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071581214822,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071581227882,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581533606,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071582203680,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071584237872,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071585315552,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071585897082,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071586230208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071586514862,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_dbbuf_dma_free"
      ],
      "caller_func": [
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues"
      ]
    },
    {
      "addr": 18446744071587605040,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587674352,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071587677968,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071587701968,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071588078272,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071588301792,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071588452240,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071588643920,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578883396,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071578990304,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579021648,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579030979,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579031627,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579033377,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579033872,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579082464,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579090640,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579144160,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579186896,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579213824,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579251120,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579258272,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579266891,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579326510,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579333122,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579333934,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579416144,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579607232,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579633743,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579683216,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579792512,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579803136,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579827824,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579851088,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579867536,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579886407,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579949034,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579999616,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580149008,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580160352,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580183628,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580183936,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580236400,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580303760,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580336272,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580394832,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580425984,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580438784,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580444352,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580775392,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580861632,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580873264,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580874656,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580876432,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580883648,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580909504,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580911792,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580916080,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581029936,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581202032,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581214822,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581227882,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581533606,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582203680,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584237872,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585315552,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585897082,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586230208,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586503440,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587605040,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587674352,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587677968,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587701968,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588078272,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588301792,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588452240,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588643920,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578877316,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071578966244,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071578966736,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579016978,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579024880,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579075504,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579121568,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579148416,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    },
    {
      "addr": 18446744071579186368,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579193456,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071579202312,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579228882,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260958,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    },
    {
      "addr": 18446744071579267822,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071579268622,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579345280,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579548105,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579562063,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579655477,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    },
    {
      "addr": 18446744071579723472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579737536,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    },
    {
      "addr": 18446744071579763701,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071579786000,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ]
    },
    {
      "addr": 18446744071579802480,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579821383,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071579886922,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071579938288,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ]
    },
    {
      "addr": 18446744071579956864,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init_nohz"
      ]
    },
    {
      "addr": 18446744071580094512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580106624,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071580131148,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580131456,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many"
      ]
    },
    {
      "addr": 18446744071580183952,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580251104,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    },
    {
      "addr": 18446744071580283536,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus"
      ]
    },
    {
      "addr": 18446744071580342000,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe"
      ]
    },
    {
      "addr": 18446744071580373056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580385856,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580391424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    },
    {
      "addr": 18446744071580721568,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071580807760,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    },
    {
      "addr": 18446744071580819392,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ]
    },
    {
      "addr": 18446744071580820784,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071580822496,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071580829712,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580855568,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580857856,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580862144,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580976016,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ]
    },
    {
      "addr": 18446744071581151301,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071581161526,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071581174554,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581475382,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071582141328,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071584173072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071585756858,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071586048576,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071586262096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/scsi/storvsc_drv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/storvsc_drv.c:storvsc_probe",
        "drivers/scsi/storvsc_drv.c:storvsc_channel_init"
      ]
    },
    {
      "addr": 18446744071586383438,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_dbbuf_dma_free"
      ],
      "caller_func": [
        "drivers/nvme/host/pci.c:nvme_probe",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues"
      ]
    },
    {
      "addr": 18446744071587374576,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587448224,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071587451440,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071587465473,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071587479926,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071587570832,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/channel_mgmt.c:init_vp_index",
        "drivers/hv/channel_mgmt.c:init_vp_index"
      ]
    },
    {
      "addr": 18446744071587791840,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071588014608,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071588164928,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071588355904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877316,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071578966244,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071578966736,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579015152,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579024880,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579075504,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579121568,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579148416,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579186368,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579193456,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579202312,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579260958,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579267822,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579268622,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579345280,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579535872,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579562063,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579611536,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579723472,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579737536,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579762400,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579786000,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579802480,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579821383,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579886922,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579938288,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579956864,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580094512,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580106624,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580131148,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580131456,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580183952,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580251104,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580283536,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580342000,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580373056,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580385856,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580391424,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580721568,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580807760,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580819392,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580820784,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580822496,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580829712,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580855568,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580857856,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580862144,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580976016,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581148784,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581161526,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581174554,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581475382,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582141328,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584173072,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585756858,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586048576,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586262096,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586372016,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587374576,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587448224,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587451440,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587465473,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587479926,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587570832,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587791840,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588014608,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588164928,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588355904,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578883332,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071578989888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579021232,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579030563,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579031211,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071579032961,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579033456,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579084098,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579090224,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579143712,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579187968,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579214896,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    },
    {
      "addr": 18446744071579252320,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579259472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071579268091,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579294546,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326430,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    },
    {
      "addr": 18446744071579333042,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071579333854,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579416064,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579617017,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579631007,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579713653,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    },
    {
      "addr": 18446744071579777280,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579791152,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    },
    {
      "addr": 18446744071579817141,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071579839312,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ]
    },
    {
      "addr": 18446744071579855792,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579874567,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071579940570,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071579991152,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ]
    },
    {
      "addr": 18446744071580140080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580151824,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071580175100,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580175408,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many"
      ]
    },
    {
      "addr": 18446744071580227872,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580295008,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    },
    {
      "addr": 18446744071580327520,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus"
      ]
    },
    {
      "addr": 18446744071580386080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe"
      ]
    },
    {
      "addr": 18446744071580417232,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580430032,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580435600,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    },
    {
      "addr": 18446744071580766640,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071580852880,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    },
    {
      "addr": 18446744071580864512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ]
    },
    {
      "addr": 18446744071580865904,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071580867680,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071580874896,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580900752,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580903040,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580907328,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581021136,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ]
    },
    {
      "addr": 18446744071581195749,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071581206022,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071581219082,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581524918,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071582194160,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071584221632,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071585504432,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071586086730,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071586487696,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071587930208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588005504,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071588009120,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071588022529,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071588035968,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071588129536,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071588410048,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071588633616,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071588784416,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071589080096,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578883332,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071578989888,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579021232,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579030563,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579031211,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579032961,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579033456,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579082048,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579090224,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579143712,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579187968,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579214896,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579252320,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579259472,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579268091,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579326430,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579333042,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579333854,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579416064,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579604512,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579631007,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579680432,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579777280,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579791152,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579815840,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579839312,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579855792,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579874567,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579940570,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579991152,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580140080,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580151824,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580175100,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580175408,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580227872,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580295008,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580327520,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580386080,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580417232,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580430032,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580435600,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580766640,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580852880,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580864512,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580865904,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580867680,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580874896,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580900752,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580903040,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580907328,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581021136,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581193232,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581206022,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581219082,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581524918,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582194160,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584221632,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585504432,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586086730,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586487696,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587930208,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588005504,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588009120,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588022529,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588035968,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588129536,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588410048,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588633616,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588784416,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589080096,
      "name": "cpumask_weight.constprop.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_weight",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578883684,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_init"
      ]
    },
    {
      "addr": 18446744071578991088,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579024800,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579034131,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    },
    {
      "addr": 18446744071579034779,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/xen/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks"
      ]
    },
    {
      "addr": 18446744071579036529,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579037024,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask",
        "arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others"
      ]
    },
    {
      "addr": 18446744071579088194,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/alternative.c:alternatives_smp_module_add"
      ]
    },
    {
      "addr": 18446744071579094400,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579148848,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/proc.c:show_cpuinfo"
      ]
    },
    {
      "addr": 18446744071579193424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ]
    },
    {
      "addr": 18446744071579220208,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ]
    },
    {
      "addr": 18446744071579257888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map",
        "arch/x86/kernel/smpboot.c:set_cpu_sibling_map"
      ]
    },
    {
      "addr": 18446744071579265072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_source"
      ]
    },
    {
      "addr": 18446744071579273691,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock",
        "arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock"
      ]
    },
    {
      "addr": 18446744071579300090,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579303378,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:physflat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334718,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    },
    {
      "addr": 18446744071579341346,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ]
    },
    {
      "addr": 18446744071579342206,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ]
    },
    {
      "addr": 18446744071579425088,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ]
    },
    {
      "addr": 18446744071579470512,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_next",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_start"
      ],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_show"
      ]
    },
    {
      "addr": 18446744071579478016,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus"
      ]
    },
    {
      "addr": 18446744071579650697,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_clamp_max_active"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071579664847,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pid_idr_init",
        "kernel/pid.c:pid_idr_init"
      ]
    },
    {
      "addr": 18446744071579758581,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpuset_cpumask_can_shrink",
        "kernel/sched/core.c:set_cpus_allowed_common"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ]
    },
    {
      "addr": 18446744071579825216,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579836112,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    },
    {
      "addr": 18446744071579862261,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sd_degenerate"
      ],
      "caller_func": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    },
    {
      "addr": 18446744071579884368,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:register_sched_domain_sysctl"
      ]
    },
    {
      "addr": 18446744071579900976,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579920087,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash"
      ]
    },
    {
      "addr": 18446744071579986842,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    },
    {
      "addr": 18446744071580037888,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/affinity.c:irq_calc_affinity_vectors",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks",
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ]
    },
    {
      "addr": 18446744071580192016,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/clockevents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:clockevents_register_device"
      ]
    },
    {
      "addr": 18446744071580204688,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_setup_sched_timer"
      ]
    },
    {
      "addr": 18446744071580227219,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init"
      ]
    },
    {
      "addr": 18446744071580227504,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_call_function_many"
      ]
    },
    {
      "addr": 18446744071580280640,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:crash_prepare_elf64_headers"
      ]
    },
    {
      "addr": 18446744071580349424,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ]
    },
    {
      "addr": 18446744071580382624,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:__stop_cpus"
      ]
    },
    {
      "addr": 18446744071580441584,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:register_kretprobe"
      ]
    },
    {
      "addr": 18446744071580472816,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580485648,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580491232,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ]
    },
    {
      "addr": 18446744071580824800,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ]
    },
    {
      "addr": 18446744071580911216,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    },
    {
      "addr": 18446744071580923056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_alloc"
      ]
    },
    {
      "addr": 18446744071580924480,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate"
      ]
    },
    {
      "addr": 18446744071580926256,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_populate"
      ]
    },
    {
      "addr": 18446744071580933488,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580959472,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580961776,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580966080,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581082496,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ]
    },
    {
      "addr": 18446744071581259029,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071581269337,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:mm_compute_batch"
      ]
    },
    {
      "addr": 18446744071581282506,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_build_alloc_info",
        "mm/percpu.c:pcpu_dump_alloc_info",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk"
      ]
    },
    {
      "addr": 18446744071581589831,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init"
      ]
    },
    {
      "addr": 18446744071582271056,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071584326464,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "lib/bucket_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/bucket_locks.c:__alloc_bucket_spinlocks"
      ]
    },
    {
      "addr": 18446744071585612416,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/time.c:xen_manage_runstate_time"
      ]
    },
    {
      "addr": 18446744071586195018,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/iommu/hyperv-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping"
      ]
    },
    {
      "addr": 18446744071586599440,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/nvdimm/region.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/region.c:nd_region_probe"
      ]
    },
    {
      "addr": 18446744071588045632,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588120944,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start"
      ]
    },
    {
      "addr": 18446744071588124560,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ]
    },
    {
      "addr": 18446744071588137995,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    },
    {
      "addr": 18446744071588151536,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    },
    {
      "addr": 18446744071588247072,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    },
    {
      "addr": 18446744071588548640,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_set_xps_queue"
      ]
    },
    {
      "addr": 18446744071588773376,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:store_rps_map"
      ]
    },
    {
      "addr": 18446744071588925008,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    },
    {
      "addr": 18446744071589119728,
      "name": "cpumask_weight",
      "external": false,
      "loc": "include/linux/cpumask.h:554",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578883684,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071578991088,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579024800,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579034131,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579034779,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579036529,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579037024,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579086144,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579094400,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579148848,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579193424,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579220208,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579257888,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579265072,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579273691,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579300090,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579334718,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579341346,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579342206,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579425088,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579463264,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579478016,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579641392,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579664847,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579714752,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579825216,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579836112,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579860960,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579884368,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579900976,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579920087,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579986842,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580037888,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580192016,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580204688,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580227219,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580227504,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580280640,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580349424,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580382624,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580441584,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580472816,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580485648,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580491232,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580824800,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580911216,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580923056,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580924480,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580926256,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580933488,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580959472,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580961776,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580966080,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581082496,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581256512,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581269337,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581282506,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581589831,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582271056,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584326464,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585612416,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586195018,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586599440,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588045632,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588120944,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588124560,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588137995,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588151536,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588247072,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588548640,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588773376,
      "name": "cpumask_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588925008,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589119728,
      "name": "cpumask_weight.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
unsigned int cpumask_weight(const struct cpumask * srcp)
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
unsigned int cpumask_weight(const struct cpumask * srcp)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int cpumask_weight(const struct cpumask * srcp)
```
</details>
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

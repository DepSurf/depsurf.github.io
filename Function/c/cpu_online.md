# Function: <code>cpu_online</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578860001,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578866570,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578987875,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008269,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013292,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update",
        "arch/x86/xen/mmu_pv.c:xen_mc_issue",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579025514,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:xen_mc_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052912,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053971,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579058001,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062850,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076059,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084975,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:nmi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579090525,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work",
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120303,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:fpu__save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125701,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145062,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184139,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579197621,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203093,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/mce/threshold.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold",
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206523,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207273,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579217115,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256140,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285997,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294395,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579300466,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305493,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311760,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:free_moved_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate",
        "arch/x86/kernel/apic/vector.c:clear_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591602578,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault",
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419156,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515926,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533099,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540907,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579549171,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579609179,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659391,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:pwq_activate_delayed_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579687132,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718039,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722621,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579727098,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579790082,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:call_trace_sched_update_nr_running",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:ttwu_do_wakeup",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:migrate_swap",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:is_cpu_allowed",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795452,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:default_idle_call",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579816887,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_group_capacity",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860353,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579914555,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938250,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:membarrier_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579956963,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:pm_qos_update_flags",
        "kernel/power/qos.c:pm_qos_update_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579963282,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579965932,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579968305,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614395771,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580018124,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu",
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580040373,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580072790,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_remove_reserved",
        "kernel/irq/matrix.c:irq_matrix_reserve",
        "kernel/irq/matrix.c:irq_matrix_assign",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/irq/matrix.c:irq_matrix_reserve_managed",
        "kernel/irq/matrix.c:irq_matrix_assign_system",
        "kernel/irq/matrix.c:irq_matrix_offline",
        "kernel/irq/matrix.c:irq_matrix_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580074921,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:trc_inspect_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580094626,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580122443,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580139079,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580142512,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580169221,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:get_next_timer_interrupt",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:detach_if_pending",
        "kernel/time/timer.c:enqueue_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580176565,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:enqueue_hrtimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580204091,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_fired"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580220764,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580230529,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:it_real_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580239391,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580245477,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:can_stop_idle_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580272208,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_single",
        "kernel/smp.c:flush_smp_call_function_queue",
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580304892,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module",
        "kernel/module.c:module_put",
        "kernel/module.c:try_module_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580370904,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580388451,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391048,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580536711,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_per_cpu",
        "kernel/debug/kdb/kdb_main.c:kdb_cpu_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551578,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580557134,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580640446,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580820060,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:action_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580844492,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580881292,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/trace/trace_kdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kdb.c:kdb_ftdump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905257,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq_work.c:irq_work_needs_cpu",
        "kernel/irq_work.c:irq_work_queue_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150178,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/devmap.c:bq_xmit_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581152683,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314573,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:rseq_ip_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330709,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355994,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367299,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_on_page_writeback_killable",
        "mm/page-writeback.c:wait_on_page_writeback",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:domain_dirty_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391367,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437713,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:do_shrink_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492515,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511992,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524988,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547424,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:compaction_defer_reset",
        "mm/compaction.c:defer_compaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580248,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:__mmap_lock_do_trace_released",
        "mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned",
        "mm/mmap_lock.c:__mmap_lock_do_trace_start_locking"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604127,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643036,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vm_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745650,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926323,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:kfree",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581960417,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008231,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582056517,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068125,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:action_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582080959,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178728,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_binprm",
        "fs/exec.c:__set_task_comm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582287815,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582386050,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_do_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:queue_io",
        "fs/fs-writeback.c:sb_clear_inode_writeback",
        "fs/fs-writeback.c:sb_mark_inode_writeback",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:wb_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582444503,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:mark_buffer_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582641920,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_file_get",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_arm_poll_handler",
        "fs/io_uring.c:io_async_wake",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:__io_async_wake",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:io_cqring_fill_event",
        "fs/io_uring.c:io_queue_async_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582674500,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582737205,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_posix",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:leases_conflict",
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786097,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/iomap/apply.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/apply.c:iomap_apply",
        "fs/iomap/apply.c:iomap_apply",
        "fs/iomap/apply.c:iomap_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792295,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_releasepage",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582800705,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582870692,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582900408,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:get_iowait_time",
        "fs/proc/stat.c:get_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582982918,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992848,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018929,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:__read_extent_tree_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583043505,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_count",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583053278,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583054656,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583065336,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583075371,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583122849,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_update_other_inode_time",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/inode.c:__ext4_journalled_invalidatepage",
        "fs/ext4/inode.c:ext4_invalidatepage",
        "fs/ext4/inode.c:ext4_readpage",
        "fs/ext4/inode.c:ext4_alloc_da_blocks",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583144477,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_getfsmap_format",
        "fs/ext4/ioctl.c:ext4_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583177843,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583242020,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583319698,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_nfs_commit_metadata",
        "fs/ext4/super.c:ext4_drop_inode",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583413654,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/ext4/fast_commit.c:ext4_fc_commit",
        "fs/ext4/fast_commit.c:ext4_fc_commit",
        "fs/ext4/fast_commit.c:ext4_fc_track_range",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431390,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_start_reserved",
        "fs/jbd2/transaction.c:jbd2__journal_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583440023,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583450174,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583471560,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:__jbd2_update_log_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583897762,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_audit_post_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497117,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584517861,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:submit_bio_checks",
        "block/blk-core.c:submit_bio_checks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584550544,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-merge.c:__blk_queue_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584574576,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_start_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584707156,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584715627,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584737314,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:rwb_trace_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584775738,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585068530,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:do_trace_rdpmc",
        "arch/x86/lib/msr.c:do_trace_read_msr",
        "arch/x86/lib/msr.c:do_trace_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585247892,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585287827,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_apply_state",
        "drivers/pwm/core.c:pwm_device_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591342280,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585678862,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586064499,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586172260,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_unprepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586258994,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586292729,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586335152,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586372996,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586643437,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:add_disk_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:__mix_pool_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586770102,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_submit_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586829717,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_aux_detach_device",
        "drivers/iommu/iommu.c:iommu_aux_attach_device",
        "drivers/iommu/iommu.c:report_iommu_fault",
        "drivers/iommu/iommu.c:__iommu_unmap",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/iommu/iommu.c:iommu_group_do_detach_device",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586917764,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586930756,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:register_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586967018,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/qos.c:__dev_pm_qos_remove_request",
        "drivers/base/power/qos.c:__dev_pm_qos_update_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586979528,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586998679,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587001966,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587054037,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_async_complete_cb",
        "drivers/base/regmap/regmap.c:_regmap_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587074562,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/regmap/regcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache.c:regcache_cache_bypass",
        "drivers/base/regmap/regcache.c:regcache_cache_only",
        "drivers/base/regmap/regcache.c:regcache_drop_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587342162,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_init",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587365364,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587392697,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587403799,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587529110,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587580727,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587684512,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587723315,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587747365,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587806438,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588243356,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588254824,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588265964,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:queue_trb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell",
        "drivers/usb/host/xhci-ring.c:inc_enq",
        "drivers/usb/host/xhci-ring.c:inc_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588298289,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322617,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_free_request",
        "drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588436410,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_set_offset",
        "drivers/rtc/interface.c:rtc_read_offset",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_alarm_disable",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/rtc/interface.c:rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588461371,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588472612,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588526551,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/hwmon/hwmon.c:hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:hwmon_attr_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588535972,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588553349,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_helpers.c:__thermal_cdev_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588561241,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/gov_fair_share.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_fair_share.c:fair_share_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588562755,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/gov_step_wise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_step_wise.c:thermal_zone_trip_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588568137,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:allocate_power",
        "drivers/thermal/gov_power_allocator.c:pid_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588571124,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588571979,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588592444,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_submit_discard_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588680968,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__split_and_process_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588739667,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588744151,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588795268,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev",
        "drivers/cpufreq/cpufreq.c:store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588838737,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588844917,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588861125,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_cqe_request_done",
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588982952,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589021834,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/devfreq.c:devfreq_set_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589062690,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/ras/ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/ras.c:log_arm_hw_error",
        "drivers/ras/ras.c:log_non_standard_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589078718,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/interconnect/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589109405,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589168032,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__consume_stateless_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589180782,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589276966,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:net_rps_send_ipi",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__dev_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589318944,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589444656,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589459876,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/core/xdp.c:mem_xa_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589477368,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589482702,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589486290,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589585000,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_report",
        "net/core/devlink.c:devlink_health_report",
        "net/core/devlink.c:devlink_health_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589680710,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dequeue_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589703816,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589760834,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:do_trace_netlink_extack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589795416,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050221,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590085671,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590103872,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590173121,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590235755,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_sk_state_store",
        "net/ipv4/af_inet.c:inet_sk_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590298023,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590650446,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_table_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590798561,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591078661,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591112015,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591124514,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/mptcp/options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options"
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
  "name": "cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578860065,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578868136,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579004372,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026314,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579031545,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update",
        "arch/x86/xen/mmu_pv.c:xen_mc_issue",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044087,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:xen_mc_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073797,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074878,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079166,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084069,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097461,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107973,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:nmi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113783,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work",
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145756,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_sync_fpstate",
        "arch/x86/kernel/fpu/core.c:fpu_sync_fpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150557,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172219,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218184,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579233311,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239519,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/mce/threshold.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold",
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243083,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244190,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579255323,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297102,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329735,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579341512,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348083,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353525,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360391,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:free_moved_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate",
        "arch/x86/kernel/apic/vector.c:clear_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592775538,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault",
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579482667,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579587635,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579605437,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579613400,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579621930,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__raise_softirq_irqoff",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685095,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:__send_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579736367,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:pwq_activate_inactive_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765431,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579796363,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579801152,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579807146,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885743,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:call_trace_sched_update_nr_running",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:ttwu_do_wakeup",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:migrate_swap",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579891388,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:default_idle_call",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579918407,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_group_capacity",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579968922,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580035966,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580063194,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:membarrier_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580086320,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:pm_qos_update_flags",
        "kernel/power/qos.c:pm_qos_update_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093051,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580096209,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580099425,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615330054,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580150377,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu",
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580172959,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206801,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_remove_reserved",
        "kernel/irq/matrix.c:irq_matrix_reserve",
        "kernel/irq/matrix.c:irq_matrix_assign",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/irq/matrix.c:irq_matrix_reserve_managed",
        "kernel/irq/matrix.c:irq_matrix_assign_system",
        "kernel/irq/matrix.c:irq_matrix_offline",
        "kernel/irq/matrix.c:irq_matrix_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580208825,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:trc_inspect_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580233296,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580265115,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580282695,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580286157,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314037,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:get_next_timer_interrupt",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:detach_if_pending",
        "kernel/time/timer.c:enqueue_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322117,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:enqueue_hrtimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580350802,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_fired"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368601,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580379470,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:it_real_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580388924,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580396149,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:can_stop_idle_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580424048,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_single",
        "kernel/smp.c:flush_smp_call_function_queue",
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580458256,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module",
        "kernel/module.c:module_put",
        "kernel/module.c:try_module_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580530818,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580550480,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553122,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580708052,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_per_cpu",
        "kernel/debug/kdb/kdb_main.c:kdb_cpu_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580721338,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580727024,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580812974,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581016908,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:action_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044297,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082196,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/trace/trace_kdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kdb.c:kdb_ftdump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581107449,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq_work.c:irq_work_needs_cpu",
        "kernel/irq_work.c:irq_work_queue_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388027,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "kernel/bpf/devmap.c:bq_xmit_all",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394715,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_generic_redirect",
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559807,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:rseq_ip_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581630,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603851,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615728,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wait_on_page_writeback_killable",
        "mm/page-writeback.c:wait_on_page_writeback",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:domain_dirty_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638793,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691191,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:do_shrink_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581751424,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771781,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786931,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581811138,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:compaction_defer_reset",
        "mm/compaction.c:compaction_deferred",
        "mm/compaction.c:defer_compaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581845221,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:__mmap_lock_do_trace_released",
        "mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned",
        "mm/mmap_lock.c:__mmap_lock_do_trace_start_locking"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870338,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911017,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vm_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023836,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223669,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:kfree",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592223838,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/kfence/report.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/report.c:kfence_report_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265237,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582310615,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582364548,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582378178,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:action_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582392521,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582496133,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_binprm",
        "fs/exec.c:__set_task_comm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582606166,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582707199,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_do_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:queue_io",
        "fs/fs-writeback.c:sb_clear_inode_writeback",
        "fs/fs-writeback.c:sb_mark_inode_writeback",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:wb_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582762772,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:mark_buffer_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582970329,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_file_get_normal",
        "fs/io_uring.c:io_drain_req",
        "fs/io_uring.c:io_arm_poll_handler",
        "fs/io_uring.c:io_async_wake",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:__io_async_wake",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:io_cqring_fill_event",
        "fs/io_uring.c:io_queue_async_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583001858,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583064114,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_posix",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:leases_conflict",
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121316,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_releasepage",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583129566,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583131609,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/iomap/iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/iter.c:iomap_iter",
        "fs/iomap/iter.c:iomap_iter_done",
        "fs/iomap/iter.c:iomap_iter_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583204323,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583234136,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:get_iowait_time",
        "fs/proc/stat.c:get_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318755,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583329200,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583355801,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:__read_extent_tree_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583380942,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_count",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583391083,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583392528,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583403361,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583413925,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583463713,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_update_other_inode_time",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/inode.c:__ext4_journalled_invalidatepage",
        "fs/ext4/inode.c:ext4_invalidatepage",
        "fs/ext4/inode.c:ext4_readpage",
        "fs/ext4/inode.c:ext4_alloc_da_blocks",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583484941,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_getfsmap_format",
        "fs/ext4/ioctl.c:ext4_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583517127,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583584049,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663250,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_nfs_commit_metadata",
        "fs/ext4/super.c:ext4_drop_inode",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583763830,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/ext4/fast_commit.c:ext4_fc_commit",
        "fs/ext4/fast_commit.c:ext4_fc_update_stats",
        "fs/ext4/fast_commit.c:ext4_fc_track_range",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583780750,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_start_reserved",
        "fs/jbd2/transaction.c:jbd2__journal_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789450,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583799929,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583825000,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_shrink_count",
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan",
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584261631,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_audit_post_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584905913,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584928140,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:submit_bio_checks",
        "block/blk-core.c:submit_bio_checks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584961851,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-merge.c:__blk_queue_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584987602,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_start_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585130602,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585143349,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585165251,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:rwb_trace_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205687,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585515263,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:do_trace_rdpmc",
        "arch/x86/lib/msr.c:do_trace_read_msr",
        "arch/x86/lib/msr.c:do_trace_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585703838,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585744550,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_apply_state",
        "drivers/pwm/core.c:pwm_device_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585886505,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586158763,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586559155,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586672094,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_set_phase",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_unprepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586769570,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586810610,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586854908,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888128,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587190701,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:add_disk_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:__mix_pool_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587325254,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_submit_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587370328,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587390178,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_aux_detach_device",
        "drivers/iommu/iommu.c:iommu_aux_attach_device",
        "drivers/iommu/iommu.c:report_iommu_fault",
        "drivers/iommu/iommu.c:__iommu_unmap",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/iommu/iommu.c:iommu_group_do_detach_device",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587480127,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587493339,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:register_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587500487,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:devm_add_action",
        "drivers/base/devres.c:devres_remove_group",
        "drivers/base/devres.c:devres_close_group",
        "drivers/base/devres.c:devres_open_group",
        "drivers/base/devres.c:release_nodes",
        "drivers/base/devres.c:devres_remove",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587533143,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/qos.c:__dev_pm_qos_remove_request",
        "drivers/base/power/qos.c:__dev_pm_qos_update_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587544437,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587564881,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587568857,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_report_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587624210,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_async_complete_cb",
        "drivers/base/regmap/regmap.c:_regmap_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587645858,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/base/regmap/regcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache.c:regcache_cache_bypass",
        "drivers/base/regmap/regcache.c:regcache_cache_only",
        "drivers/base/regmap/regcache.c:regcache_drop_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587909199,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587932368,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587964422,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587976052,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588106731,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588163318,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588274493,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588316534,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588342946,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588408430,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588891267,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588904944,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588916953,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:queue_trb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep",
        "drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell",
        "drivers/usb/host/xhci-ring.c:inc_enq",
        "drivers/usb/host/xhci-ring.c:inc_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588954204,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588980134,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_free_request",
        "drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589103907,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_set_offset",
        "drivers/rtc/interface.c:rtc_read_offset",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_alarm_disable",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/rtc/interface.c:rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589129471,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589140820,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589200388,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/hwmon/hwmon.c:hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:hwmon_attr_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589209952,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589227420,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_helpers.c:__thermal_cdev_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589235481,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/gov_fair_share.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_fair_share.c:fair_share_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237099,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/gov_step_wise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_step_wise.c:thermal_zone_trip_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242486,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:allocate_power",
        "drivers/thermal/gov_power_allocator.c:pid_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589245425,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589246484,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589268793,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_submit_discard_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589376281,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__split_and_process_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589430163,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589434612,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589487651,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev",
        "drivers/cpufreq/cpufreq.c:store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589534476,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589542541,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589563151,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_cqe_request_done",
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589694321,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589737415,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/devfreq.c:devfreq_set_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589780927,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/ras/ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/ras.c:log_arm_hw_error",
        "drivers/ras/ras.c:log_non_standard_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589797736,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "drivers/interconnect/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589827299,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:sk_error_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589888493,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__consume_stateless_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589899243,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590001543,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:net_rps_send_ipi",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_qdisc_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590049829,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179841,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590197004,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_xa_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590216321,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590222698,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590226996,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590339276,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_report",
        "net/core/devlink.c:devlink_health_report",
        "net/core/devlink.c:devlink_health_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590437320,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dequeue_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590462013,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590520079,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:do_trace_netlink_extack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590555000,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590823764,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590860308,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590877392,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590953883,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591019096,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_sk_state_store",
        "net/ipv4/af_inet.c:inet_sk_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591085049,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591458564,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_table_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591623169,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591936811,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591957224,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591971155,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:893",
      "file": "net/mptcp/options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool cpu_online(unsigned int cpu)
```

```json
{
  "name": "cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578850900,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall"
      ],
      "caller_func": [
        "init/main.c:trace_initcall_level"
      ]
    },
    {
      "addr": 18446744071578864451,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579021118,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579045606,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051493,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066211,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:xen_mc_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098926,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100148,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107386,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112848,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129158,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138565,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:nmi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145776,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work",
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187686,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_sync_fpstate",
        "arch/x86/kernel/fpu/core.c:fpu_sync_fpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192794,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig",
        "arch/x86/kernel/fpu/signal.c:fpregs_restore_userregs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194868,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpregs_restore_userregs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217370,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269362,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579283613,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290717,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/cpu/mce/threshold.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold",
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294727,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295434,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579307387,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579352494,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391424,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402510,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:wakeup_cpu0_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409679,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415797,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417975,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:free_moved_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate",
        "arch/x86/kernel/apic/vector.c:clear_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594672957,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault",
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579561589,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678594,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593866611,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698248,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579706149,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    },
    {
      "addr": 18446744071579716148,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__raise_softirq_irqoff",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579783336,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:__send_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579842078,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:pwq_activate_inactive_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872225,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905225,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579909703,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917302,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003147,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:call_trace_sched_update_nr_running",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:ttwu_do_wakeup",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:migrate_swap",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580030483,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_group_capacity",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580115658,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:do_idle",
        "kernel/sched/build_policy.c:default_idle_call",
        "kernel/sched/build_policy.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580162170,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_wait_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594719302,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594724871,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_common",
        "kernel/locking/semaphore.c:__down_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594727829,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594729140,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218714,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594735467,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580220094,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580222313,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:cpu_latency_qos_remove_request",
        "kernel/power/qos.c:pm_qos_update_flags",
        "kernel/power/qos.c:pm_qos_update_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580230402,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580234046,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580238043,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580275741,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:__pr_flush",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:printk_sprint"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init"
      ]
    },
    {
      "addr": 18446744071580295391,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu",
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580319237,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580361116,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_remove_reserved",
        "kernel/irq/matrix.c:irq_matrix_reserve",
        "kernel/irq/matrix.c:irq_matrix_assign",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/irq/matrix.c:irq_matrix_reserve_managed",
        "kernel/irq/matrix.c:irq_matrix_assign_system",
        "kernel/irq/matrix.c:irq_matrix_offline",
        "kernel/irq/matrix.c:irq_matrix_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580366025,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:trc_inspect_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406189,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:call_rcu",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks"
      ]
    },
    {
      "addr": 18446744071580435297,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580455253,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459486,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580482633,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module",
        "kernel/module/main.c:module_put",
        "kernel/module/main.c:try_module_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580524757,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:get_next_timer_interrupt",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:detach_if_pending",
        "kernel/time/timer.c:enqueue_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580533909,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:hrtimer_try_to_cancel",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:enqueue_hrtimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580565165,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_fired"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584837,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580597702,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:it_real_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606744,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580615461,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:can_stop_idle_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646748,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/smp.c:wake_up_all_idle_cpus",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_single",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580727995,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580749006,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751840,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580919398,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_per_cpu",
        "kernel/debug/kdb/kdb_main.c:kdb_cpu_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580933369,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580939274,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026561,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264762,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:action_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299623,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581343629,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/trace/trace_kdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kdb.c:kdb_ftdump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373809,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq_work.c:irq_work_needs_cpu",
        "kernel/irq_work.c:irq_work_queue_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581710862,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "kernel/bpf/devmap.c:bq_xmit_all",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581718060,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_generic_redirect",
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911501,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:rseq_ip_fixup",
        "kernel/rseq.c:rseq_update_cpu_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935384,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963543,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:wake_oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581977307,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_wait_writeback_killable",
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:domain_dirty_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582004283,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__folio_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582067759,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:do_shrink_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582139874,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_register_va"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152134,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172132,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582200048,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:compaction_defer_reset",
        "mm/compaction.c:compaction_deferred",
        "mm/compaction.c:defer_compaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238425,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:__mmap_lock_do_trace_released",
        "mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned",
        "mm/mmap_lock.c:__mmap_lock_do_trace_start_locking"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265690,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302069,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_page_drain_remote"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316151,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vm_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582378250,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582450541,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689670,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:kfree",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594002570,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/kfence/report.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/report.c:kfence_report_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734071,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582785246,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582806888,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861960,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582878620,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:action_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582903163,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583016534,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_binprm",
        "fs/exec.c:__set_task_comm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135593,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583249579,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_do_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:write_inode",
        "fs/fs-writeback.c:write_inode",
        "fs/fs-writeback.c:queue_io",
        "fs/fs-writeback.c:sb_clear_inode_writeback",
        "fs/fs-writeback.c:sb_mark_inode_writeback",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:wb_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583327184,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:mark_buffer_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583471874,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583537195,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_posix",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:leases_conflict",
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583595877,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/iomap/iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/iter.c:iomap_iter",
        "fs/iomap/iter.c:iomap_iter_done",
        "fs/iomap/iter.c:iomap_iter_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606400,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_invalidate_folio",
        "fs/iomap/buffered-io.c:iomap_release_folio",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583619084,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700520,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583732888,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:get_iowait_time",
        "fs/proc/stat.c:get_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583826384,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837697,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583866442,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:__read_extent_tree_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894509,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_count",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583905508,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583907020,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583918393,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583929660,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583987130,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_update_other_inode_time",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_release_folio",
        "fs/ext4/inode.c:__ext4_journalled_invalidate_folio",
        "fs/ext4/inode.c:ext4_invalidate_folio",
        "fs/ext4/inode.c:ext4_read_folio",
        "fs/ext4/inode.c:ext4_alloc_da_blocks",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584010917,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_getfsmap_format",
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584049659,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584121387,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584232796,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_nfs_commit_metadata",
        "fs/ext4/super.c:ext4_drop_inode",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584323300,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay_create",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/ext4/fast_commit.c:ext4_fc_commit",
        "fs/ext4/fast_commit.c:ext4_fc_update_stats",
        "fs/ext4/fast_commit.c:ext4_fc_track_range",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584344173,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_start_reserved",
        "fs/jbd2/transaction.c:jbd2__journal_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584354093,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584364404,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584392209,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_shrink_count",
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan",
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584872446,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_audit_post_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585605579,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585634365,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:submit_bio_noacct",
        "block/blk-core.c:submit_bio_noacct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665905,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:__blk_queue_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585700376,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_commit_rqs",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_add_rq_to_plug",
        "block/blk-mq.c:blk_mq_start_request",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_update_request",
        "block/blk-mq.c:blk_update_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585865668,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585875157,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585901308,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:rwb_trace_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586024662,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_register",
        "io_uring/io_uring.c:__x64_sys_io_uring_register",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_file_get_normal",
        "io_uring/io_uring.c:io_arm_poll_handler",
        "io_uring/io_uring.c:io_fail_links",
        "io_uring/io_uring.c:io_fill_cqe_aux",
        "io_uring/io_uring.c:io_cqring_event_overflow",
        "io_uring/io_uring.c:io_queue_iowq"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_sq_offload_create",
        "io_uring/io_uring.c:io_submit_fail_init",
        "io_uring/io_uring.c:io_drain_req"
      ]
    },
    {
      "addr": 18446744071586666653,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:do_trace_rdpmc",
        "arch/x86/lib/msr.c:do_trace_read_msr",
        "arch/x86/lib/msr.c:do_trace_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586871679,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586928164,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_apply_state",
        "drivers/pwm/core.c:pwm_device_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587081728,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587392480,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587818878,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587944067,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_phase_nolock",
        "drivers/clk/clk.c:clk_core_set_phase_nolock",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_unprepare"
      ],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree"
      ]
    },
    {
      "addr": 18446744071588047545,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588092926,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588141974,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588177383,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588639862,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_submit_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588681460,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588699330,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:report_iommu_fault",
        "drivers/iommu/iommu.c:__iommu_unmap",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/iommu/iommu.c:iommu_group_do_detach_device",
        "drivers/iommu/iommu.c:__iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588800677,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588816587,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:register_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588821895,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/base/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:devm_add_action",
        "drivers/base/devres.c:devres_remove_group",
        "drivers/base/devres.c:devres_close_group",
        "drivers/base/devres.c:devres_open_group",
        "drivers/base/devres.c:release_nodes",
        "drivers/base/devres.c:devres_remove",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588864757,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/base/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/qos.c:__dev_pm_qos_remove_request",
        "drivers/base/power/qos.c:__dev_pm_qos_update_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588878022,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588898774,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588901131,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588968812,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_async_complete_cb",
        "drivers/base/regmap/regmap.c:_regmap_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588990002,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/base/regmap/regcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache.c:regcache_cache_bypass",
        "drivers/base/regmap/regcache.c:regcache_cache_only",
        "drivers/base/regmap/regcache.c:regcache_drop_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589259982,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589283794,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589320509,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589339140,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_done_internal",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589484858,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589548499,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_done",
        "drivers/ata/libata-eh.c:ata_eh_about_to_do",
        "drivers/ata/libata-eh.c:__ata_port_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589578680,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_port_intr",
        "drivers/ata/libata-sff.c:ata_bmdma_port_intr",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:__ata_sff_port_intr",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_tf_to_host",
        "drivers/ata/libata-sff.c:ata_tf_to_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589602811,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_irq_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589656759,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589707301,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589733433,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589806075,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590319706,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590334281,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590348061,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:queue_trb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell",
        "drivers/usb/host/xhci-ring.c:inc_enq",
        "drivers/usb/host/xhci-ring.c:inc_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590386259,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590412906,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_free_request",
        "drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590549659,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_set_offset",
        "drivers/rtc/interface.c:rtc_read_offset",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_alarm_disable",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/rtc/interface.c:rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:rtc_initialize_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590578775,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590592244,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590660515,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/hwmon/hwmon.c:hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:hwmon_attr_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590673839,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:handle_thermal_trip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590691028,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_helpers.c:__thermal_cdev_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590700058,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/thermal/gov_fair_share.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_fair_share.c:get_trip_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590702203,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/thermal/gov_step_wise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_step_wise.c:thermal_zone_trip_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590708077,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:allocate_power",
        "drivers/thermal/gov_power_allocator.c:pid_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590711487,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590713595,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590748583,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_submit_discard_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590849456,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_submit_bio_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590908016,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590913177,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590969209,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev",
        "drivers/cpufreq/cpufreq.c:store",
        "drivers/cpufreq/cpufreq.c:cpufreq_notify_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590999362,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591026148,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591035363,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591058256,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_cqe_request_done",
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591201004,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "drivers/platform/chrome/cros_ec_proto.c:send_command",
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591249266,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/devfreq.c:devfreq_set_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591291881,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/ras/ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/ras.c:log_arm_hw_error",
        "drivers/ras/ras.c:log_non_standard_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591311869,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "drivers/interconnect/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591352278,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:sk_error_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591427278,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:__consume_stateless_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591428635,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591544173,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:net_rps_send_ipi",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_qdisc_enqueue",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:dev_hard_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591593936,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591742299,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591759976,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591773682,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_receive",
        "net/core/gro.c:napi_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591792778,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591800090,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591803635,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591897036,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_report",
        "net/core/devlink.c:devlink_health_report",
        "net/core/devlink.c:devlink_health_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592041426,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dequeue_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592064604,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592123449,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:do_trace_netlink_extack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592169297,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592459647,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592472329,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_rtx_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592515138,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592541176,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_ca_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592593886,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592665526,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_sk_state_store",
        "net/ipv4/af_inet.c:inet_sk_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592735121,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593140719,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_table_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593315962,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593662204,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593684249,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593696307,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/mptcp/options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:ack_update_msk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593751928,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593765143,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:919",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:__mctp_key_done_in"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578848368,
      "name": "cpu_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579699216,
      "name": "cpu_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580265632,
      "name": "cpu_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580385904,
      "name": "cpu_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585944432,
      "name": "cpu_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071594291574,
      "name": "cpu_online",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool cpu_online(unsigned int cpu)
```

```json
{
  "name": "cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627479643,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls",
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578867123,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048892,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075382,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082725,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098451,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:xen_mc_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135126,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136696,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144810,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151529,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170215,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182193,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:nmi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190960,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work",
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243606,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_sync_fpstate",
        "arch/x86/kernel/fpu/core.c:fpu_sync_fpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248957,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253053,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpstate_realloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282790,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332146,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579348989,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356509,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/cpu/mce/threshold.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold",
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360951,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427561,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579469808,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579482789,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/smpboot.c:wakeup_cpu0_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491420,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579498677,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501159,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:free_moved_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate",
        "arch/x86/kernel/apic/vector.c:clear_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596407510,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault",
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668981,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579798880,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579806489,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823265,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:cpuhp_issue_call",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831701,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    },
    {
      "addr": 18446744071579843012,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__raise_softirq_irqoff",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579915965,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:__send_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579979870,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:pwq_activate_inactive_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580015148,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580057993,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580063159,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580071702,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580165531,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:call_trace_sched_update_nr_running",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:send_call_function_single_ipi",
        "kernel/sched/core.c:ttwu_do_wakeup",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:migrate_swap",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580208688,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_cpu_capacity",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:detach_entity_load_avg",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580289166,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:do_idle",
        "kernel/sched/build_policy.c:default_idle_call",
        "kernel/sched/build_policy.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580344938,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_wait_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596469546,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596475703,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_common",
        "kernel/locking/semaphore.c:__down_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596479335,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596480822,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596501034,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596487331,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596502558,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580413097,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:cpu_latency_qos_remove_request",
        "kernel/power/qos.c:pm_qos_update_flags",
        "kernel/power/qos.c:pm_qos_update_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580422991,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580427597,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580432399,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627780183,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:printk_sprint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580506959,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu",
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580533397,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584108,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_remove_reserved",
        "kernel/irq/matrix.c:irq_matrix_reserve",
        "kernel/irq/matrix.c:irq_matrix_assign",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/irq/matrix.c:irq_matrix_reserve_managed",
        "kernel/irq/matrix.c:irq_matrix_assign_system",
        "kernel/irq/matrix.c:irq_matrix_offline",
        "kernel/irq/matrix.c:irq_matrix_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580595657,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:trc_check_slow_task",
        "kernel/rcu/update.c:trc_inspect_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580641971,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580677669,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580702005,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580706590,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732392,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module",
        "kernel/module/main.c:module_put",
        "kernel/module/main.c:try_module_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580780888,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:get_next_timer_interrupt",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:detach_if_pending",
        "kernel/time/timer.c:enqueue_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790373,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:hrtimer_try_to_cancel",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:enqueue_hrtimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580825405,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_fired"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580846501,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580860518,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:it_real_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870600,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880373,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:can_stop_idle_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913660,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/smp.c:wake_up_all_idle_cpus",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_single",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003611,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026326,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029325,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581211755,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_per_cpu",
        "kernel/debug/kdb/kdb_main.c:kdb_cpu_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226297,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581232636,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335738,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583370,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:action_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624807,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677224,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/trace/trace_kdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kdb.c:kdb_ftdump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581716599,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/trace/rv/monitors/wwnr/wwnr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr",
        "kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721601,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq_work.c:irq_work_needs_cpu",
        "kernel/irq_work.c:irq_work_queue_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117278,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "kernel/bpf/devmap.c:bq_xmit_all",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124743,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_generic_redirect",
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582347301,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:rseq_ip_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362715,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582397079,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:wake_oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412347,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_wait_writeback_killable",
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:domain_dirty_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582444336,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539896,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:do_shrink_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582617362,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_register_va"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629357,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_setup_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582653041,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_large_node",
        "mm/slab_common.c:kmalloc_large",
        "mm/slab_common.c:kmalloc_node_trace",
        "mm/slab_common.c:kmalloc_trace",
        "mm/slab_common.c:kfree",
        "mm/slab_common.c:__kmalloc_node_track_caller",
        "mm/slab_common.c:__kmalloc_node_track_caller",
        "mm/slab_common.c:__kmalloc",
        "mm/slab_common.c:__kmalloc",
        "mm/slab_common.c:__kmalloc_node",
        "mm/slab_common.c:__kmalloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582686381,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:compaction_defer_reset",
        "mm/compaction.c:compaction_deferred",
        "mm/compaction.c:defer_compaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582728521,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:__mmap_lock_do_trace_released",
        "mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned",
        "mm/mmap_lock.c:__mmap_lock_do_trace_start_locking"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757696,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796565,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_page_drain_remote"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582818476,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:vm_unmapped_area",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_mas_remove",
        "mm/mmap.c:vma_mas_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582882628,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582893737,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582960141,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220385,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240177,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/kfence/report.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/report.c:kfence_report_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258359,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318238,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583345417,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583409352,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583428147,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:action_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455291,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583580550,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_binprm",
        "fs/exec.c:__set_task_comm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583706857,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583832049,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_do_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:write_inode",
        "fs/fs-writeback.c:write_inode",
        "fs/fs-writeback.c:queue_io",
        "fs/fs-writeback.c:sb_clear_inode_writeback",
        "fs/fs-writeback.c:sb_mark_inode_writeback",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:wb_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583913136,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:mark_buffer_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584065231,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_pmd_load_hole",
        "fs/dax.c:dax_pmd_load_hole",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584137659,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_posix",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:leases_conflict",
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584201143,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/iomap/iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/iter.c:iomap_iter",
        "fs/iomap/iter.c:iomap_iter_done",
        "fs/iomap/iter.c:iomap_iter_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584210959,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_invalidate_folio",
        "fs/iomap/buffered-io.c:iomap_release_folio",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584222669,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584310856,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584345960,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:get_iowait_time",
        "fs/proc/stat.c:get_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584449051,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584461169,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584490720,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:__read_extent_tree_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584519661,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_count",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584531173,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584532764,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584544509,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584556810,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616314,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_update_other_inode_time",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_release_folio",
        "fs/ext4/inode.c:__ext4_journalled_invalidate_folio",
        "fs/ext4/inode.c:ext4_invalidate_folio",
        "fs/ext4/inode.c:ext4_read_folio",
        "fs/ext4/inode.c:ext4_alloc_da_blocks",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584641353,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_getfsmap_format",
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584681684,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584754964,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584876332,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_nfs_commit_metadata",
        "fs/ext4/super.c:ext4_drop_inode",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584971499,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/ext4/fast_commit.c:ext4_fc_commit",
        "fs/ext4/fast_commit.c:ext4_fc_update_stats",
        "fs/ext4/fast_commit.c:ext4_fc_track_range",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584993887,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_start_reserved",
        "fs/jbd2/transaction.c:jbd2__journal_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585005663,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585015492,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585045762,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_shrink_count",
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan",
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585577822,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_audit_post_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586373961,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586405584,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:submit_bio_noacct",
        "block/blk-core.c:submit_bio_noacct_nocheck"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586441471,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:__bio_split_to_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586479900,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_commit_rqs",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_add_rq_to_plug",
        "block/blk-mq.c:blk_add_rq_to_plug",
        "block/blk-mq.c:blk_mq_start_request",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_update_request",
        "block/blk-mq.c:blk_update_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586647063,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586660053,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586689279,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:rwb_trace_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586760845,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_register",
        "io_uring/io_uring.c:__x64_sys_io_uring_register",
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_submit_fail_init",
        "io_uring/io_uring.c:io_file_get_normal",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:__io_run_local_work",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:io_fill_cqe_aux",
        "io_uring/io_uring.c:io_cqring_event_overflow",
        "io_uring/io_uring.c:io_queue_iowq",
        "io_uring/io_uring.c:__io_fill_cqe_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586813340,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "io_uring/timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_disarm_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586819775,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_offload_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586831151,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:io_arm_poll_handler",
        "io_uring/poll.c:__io_poll_execute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859867,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:__io_fill_cqe_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587915085,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:do_trace_rdpmc",
        "arch/x86/lib/msr.c:do_trace_read_msr",
        "arch/x86/lib/msr.c:do_trace_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588020019,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588084075,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_apply_state",
        "drivers/pwm/core.c:pwm_device_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588269165,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588645636,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589161397,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589301827,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_phase_nolock",
        "drivers/clk/clk.c:clk_core_set_phase_nolock",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_hw_round_rate",
        "drivers/clk/clk.c:clk_hw_round_rate",
        "drivers/clk/clk.c:clk_core_round_rate_nolock",
        "drivers/clk/clk.c:clk_core_round_rate_nolock",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589426249,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589478007,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589531782,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589573503,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590110087,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_submit_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590158716,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179458,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:report_iommu_fault",
        "drivers/iommu/iommu.c:__iommu_unmap",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/iommu/iommu.c:iommu_group_do_detach_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590297238,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590315339,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:register_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590321207,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/base/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:devm_add_action",
        "drivers/base/devres.c:devres_remove_group",
        "drivers/base/devres.c:devres_close_group",
        "drivers/base/devres.c:devres_open_group",
        "drivers/base/devres.c:release_nodes",
        "drivers/base/devres.c:devres_remove",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590372613,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/base/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/qos.c:__dev_pm_qos_remove_request",
        "drivers/base/power/qos.c:__dev_pm_qos_update_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590386326,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590409554,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590414315,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590488540,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_async_complete_cb",
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:_regmap_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:_regmap_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590511602,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/base/regmap/regcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache.c:regcache_cache_bypass",
        "drivers/base/regmap/regcache.c:regcache_cache_only",
        "drivers/base/regmap/regcache.c:regcache_drop_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590822366,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590845442,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590886232,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590905560,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_done_internal",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590994591,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591066362,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591140024,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_done",
        "drivers/ata/libata-eh.c:ata_eh_about_to_do",
        "drivers/ata/libata-eh.c:__ata_port_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591172696,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_port_intr",
        "drivers/ata/libata-sff.c:ata_bmdma_port_intr",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:__ata_sff_port_intr",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_tf_to_host",
        "drivers/ata/libata-sff.c:ata_tf_to_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591201355,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_irq_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591260695,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591322197,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591349209,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591461011,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591945638,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591962518,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591978029,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:queue_trb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell",
        "drivers/usb/host/xhci-ring.c:inc_enq",
        "drivers/usb/host/xhci-ring.c:inc_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592020564,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592050775,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_free_request",
        "drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592203403,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_set_offset",
        "drivers/rtc/interface.c:rtc_read_offset",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_alarm_disable",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/rtc/interface.c:rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:rtc_initialize_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592235807,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592251057,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592327795,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/hwmon/hwmon.c:hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:hwmon_attr_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592336549,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:handle_thermal_trip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592361140,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_helpers.c:__thermal_cdev_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592371018,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/thermal/gov_fair_share.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_fair_share.c:get_trip_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592372879,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/thermal/gov_step_wise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_step_wise.c:thermal_zone_trip_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592379052,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:allocate_power",
        "drivers/thermal/gov_power_allocator.c:pid_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592382671,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592385051,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592391511,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/watchdog/watchdog_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592400150,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592421671,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_submit_discard_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592540608,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_submit_bio_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592604544,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592611316,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592673756,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_notify_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592707082,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592737894,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592746949,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592762522,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/cpuidle/governors/haltpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592771168,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_cqe_request_done",
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592941691,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593002370,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/devfreq.c:devfreq_set_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593041993,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/ras/ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/ras.c:log_arm_hw_error",
        "drivers/ras/ras.c:log_non_standard_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593064178,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "drivers/interconnect/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593123208,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:sk_error_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593193566,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:kfree_skb_reason",
        "net/core/skbuff.c:kfree_skb_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593195051,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593317769,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:net_rps_send_ipi",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_qdisc_enqueue",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:dev_hard_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593374864,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593531808,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593550536,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593565506,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_receive",
        "net/core/gro.c:napi_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593586666,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593594666,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593598755,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593700280,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_report",
        "net/core/devlink.c:devlink_health_report",
        "net/core/devlink.c:devlink_health_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593858914,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dequeue_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593884515,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593946153,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:do_trace_netlink_extack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593997473,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594313983,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594327897,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_rtx_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594371328,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594399832,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_ca_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594457719,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594533126,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_sk_state_store",
        "net/ipv4/af_inet.c:inet_sk_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594605913,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595038095,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_table_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595220873,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595592652,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595615402,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595629875,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/mptcp/options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:ack_update_msk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595688902,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595704001,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:__mctp_key_done_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595822103,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1028",
      "file": "lib/maple_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mt_find",
        "lib/maple_tree.c:mtree_erase",
        "lib/maple_tree.c:mtree_store_range",
        "lib/maple_tree.c:mtree_load",
        "lib/maple_tree.c:mas_store_prealloc",
        "lib/maple_tree.c:mas_store_gfp",
        "lib/maple_tree.c:mas_store",
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_wr_slot_store",
        "lib/maple_tree.c:mas_wr_node_store",
        "lib/maple_tree.c:mas_is_span_wr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824464,
      "name": "cpu_online",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool cpu_online(unsigned int cpu)
```

```json
{
  "name": "cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619223163,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls",
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578865090,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048892,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075222,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082869,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098119,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:xen_mc_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136059,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137592,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145418,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153641,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173463,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187063,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:nmi_backtrace_stall_check",
        "arch/x86/kernel/nmi.c:nmi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195152,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work",
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249958,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_sync_fpstate",
        "arch/x86/kernel/fpu/core.c:fpu_sync_fpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256616,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259550,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579289302,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579340850,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579357853,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365645,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/cpu/mce/threshold.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold",
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370135,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439513,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579481856,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503672,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579510853,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579513319,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:__send_cleanup_vector",
        "arch/x86/kernel/apic/vector.c:free_moved_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate",
        "arch/x86/kernel/apic/vector.c:clear_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596939270,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault",
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579682949,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579847023,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854585,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872337,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880773,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    },
    {
      "addr": 18446744071579893012,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__raise_softirq_irqoff",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579965784,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:__send_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580028974,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:pwq_activate_inactive_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580068892,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100533,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notifier_call_chain",
        "kernel/notifier.c:notifier_chain_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580112441,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580117591,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580213931,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:call_trace_sched_update_nr_running",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:call_function_single_prep_ipi",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:migrate_swap",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580267125,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_group_capacity",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:detach_entity_load_avg",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580356534,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:do_idle",
        "kernel/sched/build_policy.c:default_idle_call",
        "kernel/sched/build_policy.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580412048,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_wait_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597011389,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597017287,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_common",
        "kernel/locking/semaphore.c:__down_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597020891,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597022374,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597038617,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597028851,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597040046,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580481785,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:cpu_latency_qos_remove_request",
        "kernel/power/qos.c:pm_qos_update_flags",
        "kernel/power/qos.c:pm_qos_update_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580492367,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580496902,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501631,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619543063,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:printk_sprint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580579103,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu",
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606709,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657027,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_remove_reserved",
        "kernel/irq/matrix.c:irq_matrix_reserve",
        "kernel/irq/matrix.c:irq_matrix_assign",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/irq/matrix.c:irq_matrix_reserve_managed",
        "kernel/irq/matrix.c:irq_matrix_assign_system",
        "kernel/irq/matrix.c:irq_matrix_offline",
        "kernel/irq/matrix.c:irq_matrix_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580669161,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:trc_check_slow_task",
        "kernel/rcu/update.c:trc_inspect_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710115,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580754181,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580778757,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580783422,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580811419,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module",
        "kernel/module/main.c:module_put",
        "kernel/module/main.c:try_module_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817496,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/module/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580863875,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:get_next_timer_interrupt",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:detach_if_pending",
        "kernel/time/timer.c:enqueue_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580873605,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:enqueue_hrtimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908973,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_fired"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580929973,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944278,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:it_real_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954360,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964901,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:can_stop_idle_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998828,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/smp.c:wake_up_all_idle_cpus",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_single",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:generic_exec_single",
        "kernel/smp.c:generic_exec_single",
        "kernel/smp.c:generic_exec_single",
        "kernel/smp.c:__smp_call_single_queue",
        "kernel/smp.c:__smp_call_single_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092203,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114678,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117693,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306091,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_per_cpu",
        "kernel/debug/kdb/kdb_main.c:kdb_cpu_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320649,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581326970,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430660,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563135,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:trace_sched_switch_callback",
        "kernel/trace/trace_osnoise.c:trace_softirq_exit_callback",
        "kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit",
        "kernel/trace/trace_osnoise.c:trace_osnoise_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704522,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:action_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764332,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581818744,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/trace/trace_kdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kdb.c:kdb_ftdump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875271,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/trace/rv/monitors/wwnr/wwnr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr",
        "kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880385,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq_work.c:irq_work_needs_cpu",
        "kernel/irq_work.c:irq_work_queue_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582313406,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "kernel/bpf/devmap.c:bq_xmit_all",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321015,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_generic_redirect",
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550022,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:rseq_ip_fixup",
        "kernel/rseq.c:rseq_update_cpu_node_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582566015,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582602951,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:wake_oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582618811,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_wait_writeback_killable",
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:domain_dirty_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582649437,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749509,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:do_shrink_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826098,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_register_va"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838221,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_setup_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862657,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_large_node",
        "mm/slab_common.c:kmalloc_large",
        "mm/slab_common.c:kmalloc_node_trace",
        "mm/slab_common.c:kmalloc_trace",
        "mm/slab_common.c:kfree",
        "mm/slab_common.c:__kmalloc_node_track_caller",
        "mm/slab_common.c:__kmalloc_node_track_caller",
        "mm/slab_common.c:__kmalloc",
        "mm/slab_common.c:__kmalloc",
        "mm/slab_common.c:__kmalloc_node",
        "mm/slab_common.c:__kmalloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582895976,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:compaction_defer_reset",
        "mm/compaction.c:compaction_deferred",
        "mm/compaction.c:defer_compaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944713,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:__mmap_lock_do_trace_released",
        "mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned",
        "mm/mmap_lock.c:__mmap_lock_do_trace_start_locking"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582973467,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583010949,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_drain_remote"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032833,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:vm_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583097709,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583109015,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583177087,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcppages_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583398981,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:__ksm_enter",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:remove_node_from_stable_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583438919,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583459574,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/kfence/report.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/report.c:kfence_report_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583479047,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536756,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583567119,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629608,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583649179,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:action_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583675076,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583795865,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_binprm",
        "fs/exec.c:__set_task_comm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583924280,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584050055,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_do_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:write_inode",
        "fs/fs-writeback.c:write_inode",
        "fs/fs-writeback.c:queue_io",
        "fs/fs-writeback.c:sb_clear_inode_writeback",
        "fs/fs-writeback.c:sb_mark_inode_writeback",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:wb_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584121630,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:mark_buffer_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584291641,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_pmd_load_hole",
        "fs/dax.c:dax_pmd_load_hole",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584364849,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_posix",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:leases_conflict",
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584431223,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/iomap/iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/iter.c:iomap_iter",
        "fs/iomap/iter.c:iomap_iter_done",
        "fs/iomap/iter.c:iomap_iter_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584440688,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_release_folio",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450929,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584540679,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584576184,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:get_iowait_time",
        "fs/proc/stat.c:get_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584677693,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690180,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584719424,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:__read_extent_tree_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584748386,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_count",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584760099,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584761801,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584773445,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584785580,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584843050,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_update_other_inode_time",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_release_folio",
        "fs/ext4/inode.c:__ext4_journalled_invalidate_folio",
        "fs/ext4/inode.c:ext4_invalidate_folio",
        "fs/ext4/inode.c:ext4_read_folio",
        "fs/ext4/inode.c:ext4_alloc_da_blocks",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584863913,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_getfsmap_format",
        "fs/ext4/ioctl.c:ext4_force_shutdown",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584907051,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584978676,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585103548,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_nfs_commit_metadata",
        "fs/ext4/super.c:ext4_drop_inode",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585199674,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/ext4/fast_commit.c:ext4_fc_commit",
        "fs/ext4/fast_commit.c:ext4_fc_update_stats",
        "fs/ext4/fast_commit.c:ext4_fc_track_range",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585221887,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_start_reserved",
        "fs/jbd2/transaction.c:jbd2__journal_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231846,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585243156,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585274706,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_shrink_count",
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan",
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585809102,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_audit_post_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586620428,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586652577,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:submit_bio_noacct",
        "block/blk-core.c:submit_bio_noacct_nocheck"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586688607,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:__bio_split_to_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586723970,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-mq.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_add_rq_to_plug",
        "block/blk-mq.c:blk_add_rq_to_plug",
        "block/blk-mq.c:blk_mq_start_request",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_account_io_done",
        "block/blk-mq.c:blk_update_request",
        "block/blk-mq.c:blk_update_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586908115,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586922694,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586950266,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:rwb_trace_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587027527,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__do_sys_io_uring_register",
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_submit_fail_init",
        "io_uring/io_uring.c:io_file_get_normal",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:__io_run_local_work",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:io_fill_cqe_aux",
        "io_uring/io_uring.c:io_cqring_event_overflow",
        "io_uring/io_uring.c:io_queue_iowq",
        "io_uring/io_uring.c:__io_fill_cqe_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587079785,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "io_uring/timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_disarm_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086204,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_offload_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587097905,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:io_arm_poll_handler",
        "io_uring/poll.c:__io_poll_execute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587126110,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:__io_fill_cqe_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588189117,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:do_trace_rdpmc",
        "arch/x86/lib/msr.c:do_trace_read_msr",
        "arch/x86/lib/msr.c:do_trace_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588294419,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588358568,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwm_apply_state",
        "drivers/pwm/core.c:pwm_device_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588544748,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:cper_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588933328,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589454709,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589599491,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_phase_nolock",
        "drivers/clk/clk.c:clk_core_set_phase_nolock",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_hw_round_rate",
        "drivers/clk/clk.c:clk_hw_round_rate",
        "drivers/clk/clk.c:clk_core_round_rate_nolock",
        "drivers/clk/clk.c:clk_core_round_rate_nolock",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589725401,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589778343,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589832854,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589876223,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590423831,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_submit_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590472948,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590501522,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:report_iommu_fault",
        "drivers/iommu/iommu.c:__iommu_unmap",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/iommu/iommu.c:iommu_group_add_device",
        "drivers/iommu/iommu.c:__iommu_group_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590617229,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590635179,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:register_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590641079,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/base/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:__devm_add_action",
        "drivers/base/devres.c:devres_remove_group",
        "drivers/base/devres.c:devres_close_group",
        "drivers/base/devres.c:devres_open_group",
        "drivers/base/devres.c:release_nodes",
        "drivers/base/devres.c:devres_remove",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590693061,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/base/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/qos.c:__dev_pm_qos_remove_request",
        "drivers/base/power/qos.c:__dev_pm_qos_update_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590706112,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590729122,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590733851,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590811116,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_async_complete_cb",
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:_regmap_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:_regmap_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590835778,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/base/regmap/regcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache.c:regcache_cache_bypass",
        "drivers/base/regmap/regcache.c:regcache_cache_only",
        "drivers/base/regmap/regcache.c:regcache_drop_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591164350,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked",
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591188697,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591229563,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591249752,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_done_internal",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591348889,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591421856,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591498480,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_done",
        "drivers/ata/libata-eh.c:ata_eh_about_to_do",
        "drivers/ata/libata-eh.c:__ata_port_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591533608,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_port_intr",
        "drivers/ata/libata-sff.c:ata_bmdma_port_intr",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:__ata_sff_port_intr",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_tf_to_host",
        "drivers/ata/libata-sff.c:ata_tf_to_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591560667,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_irq_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591615559,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591685073,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_c45_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_c45_read",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591710937,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591753999,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "drivers/net/virtio_net.c:virtnet_xdp_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591876560,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592368402,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592383566,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592399453,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:queue_trb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_port_status",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell",
        "drivers/usb/host/xhci-ring.c:inc_enq",
        "drivers/usb/host/xhci-ring.c:inc_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592440314,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592473524,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_free_request",
        "drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592627611,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_set_offset",
        "drivers/rtc/interface.c:rtc_read_offset",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_alarm_disable",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:rtc_initialize_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592660751,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592676299,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592754643,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/hwmon/hwmon.c:hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:hwmon_attr_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592769098,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592788708,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_helpers.c:__thermal_cdev_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592799282,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/thermal/gov_fair_share.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_fair_share.c:fair_share_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592800852,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/thermal/gov_step_wise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_step_wise.c:thermal_zone_trip_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592807052,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:allocate_power",
        "drivers/thermal/gov_power_allocator.c:pid_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592810639,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592811947,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592820639,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/watchdog/watchdog_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592829546,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592847335,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_submit_discard_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592971746,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_submit_bio_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593035107,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593041918,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593104572,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_notify_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593142277,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593174998,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596943204,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593198634,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/cpuidle/governors/haltpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593207488,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_cqe_request_done",
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593391451,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593453842,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/devfreq.c:devfreq_set_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593494089,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/ras/ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/ras.c:log_arm_hw_error",
        "drivers/ras/ras.c:log_non_standard_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593516242,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "drivers/interconnect/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593530285,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:call_trace_sock_recv_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593563419,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:sk_error_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593652814,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "net/core/skbuff.c:kfree_skb_reason",
        "net/core/skbuff.c:kfree_skb_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593654379,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593779434,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:net_rps_send_ipi",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_qdisc_enqueue",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:dev_hard_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593837142,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593999424,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594019336,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594034439,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_receive",
        "net/core/gro.c:napi_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594059690,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594068026,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594072118,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594187310,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_data_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594233778,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:__qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dequeue_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594253993,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594322409,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:do_trace_netlink_extack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594373681,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594700399,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594713705,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_rtx_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594761398,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594788152,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_ca_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594849063,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594924902,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_sk_state_store",
        "net/ipv4/af_inet.c:inet_sk_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594997828,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595259314,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_data_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595431517,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_table_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595525643,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595616744,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595813592,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/devlink/leftover.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devlink_trap_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595916696,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/devlink/health.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_health_report",
        "net/devlink/health.c:devlink_health_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596101787,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596129839,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_data_ready",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596138995,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/mptcp/options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:ack_update_msk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596201878,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596215619,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:__mctp_key_done_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596222665,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/handshake/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/netlink.c:handshake_nl_done_doit",
        "net/handshake/netlink.c:handshake_nl_done_doit",
        "net/handshake/netlink.c:handshake_nl_accept_doit",
        "net/handshake/netlink.c:handshake_nl_accept_doit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596226692,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "net/handshake/request.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_complete",
        "net/handshake/request.c:handshake_req_submit",
        "net/handshake/request.c:handshake_req_submit",
        "net/handshake/request.c:handshake_req_submit",
        "net/handshake/request.c:handshake_sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596328388,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1080",
      "file": "lib/maple_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mt_find",
        "lib/maple_tree.c:mtree_erase",
        "lib/maple_tree.c:mtree_store_range",
        "lib/maple_tree.c:mtree_load",
        "lib/maple_tree.c:mas_store_prealloc",
        "lib/maple_tree.c:mas_store_gfp",
        "lib/maple_tree.c:mas_store",
        "lib/maple_tree.c:mas_wr_modify",
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_wr_node_store",
        "lib/maple_tree.c:mas_is_span_wr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873648,
      "name": "cpu_online",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool cpu_online(unsigned int cpu)
```

```json
{
  "name": "cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621512880,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:kernel_init_freeable",
        "init/main.c:do_initcalls",
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578875602,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074220,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100678,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr0",
        "arch/x86/xen/enlighten_pv.c:xen_load_sp0",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_load_idt",
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_set_ldt",
        "arch/x86/xen/enlighten_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108661,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_all",
        "arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user",
        "arch/x86/xen/mmu_pv.c:xen_flush_tlb",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_unpin",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_pin",
        "arch/x86/xen/mmu_pv.c:xen_set_p4d",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op",
        "arch/x86/xen/mmu_pv.c:xen_extend_mmu_update",
        "arch/x86/xen/mmu_pv.c:xen_mc_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123911,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/xen/multicalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_callback",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:xen_mc_extend_args",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:__xen_mc_entry",
        "arch/x86/xen/multicalls.c:xen_mc_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162352,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164015,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173934,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_one",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182937,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202694,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_thermal",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216279,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:nmi_backtrace_stall_check",
        "arch/x86/kernel/nmi.c:nmi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224431,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work",
        "arch/x86/kernel/irq_work.c:__sysvec_irq_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279382,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:fpregs_lock_and_load",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:fpu_sync_fpstate",
        "arch/x86/kernel/fpu/core.c:fpu_sync_fpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286504,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289925,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579318566,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371266,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579387756,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395564,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/cpu/mce/threshold.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold",
        "arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401639,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/cpu/mce/dev-mcelog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579469142,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503329,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/cpu/debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/debugfs.c:cpu_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579511983,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function_single",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:__sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532862,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:handle_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579538709,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579541783,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:__vector_schedule_cleanup",
        "arch/x86/kernel/apic/vector.c:free_moved_vector",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_activate",
        "arch/x86/kernel/apic/vector.c:x86_vector_deactivate",
        "arch/x86/kernel/apic/vector.c:clear_irq_vector",
        "arch/x86/kernel/apic/vector.c:assign_managed_vector",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:assign_vector_locked",
        "arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_vector",
        "arch/x86/kernel/apic/vector.c:apic_update_irq_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597864838,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault",
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717397,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:flush_tlb_func",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579884815,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579892393,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910257,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579923029,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": [
        "kernel/exit.c:do_exit"
      ]
    },
    {
      "addr": 18446744071579931700,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__raise_softirq_irqoff",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005112,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:__send_signal_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580071902,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:work_on_cpu_safe_key",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:pwq_activate_inactive_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580111676,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580145349,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:notifier_call_chain",
        "kernel/notifier.c:notifier_chain_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580157593,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:migrate_to_reboot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580163159,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:smpboot_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580262635,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:call_trace_sched_update_nr_running",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:sched_tick_remote",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:call_function_single_prep_ipi",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:migrate_swap",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580337298,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_group_capacity",
        "kernel/sched/fair.c:compute_energy",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:detach_entity_load_avg",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/fair.c:update_curr_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580422131,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:do_idle",
        "kernel/sched/build_policy.c:default_idle_call",
        "kernel/sched/build_policy.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469212,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_enqueue_sleeper",
        "kernel/sched/build_utility.c:__update_stats_wait_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597940733,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597946631,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_common",
        "kernel/locking/semaphore.c:__down_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597950235,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597951718,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597970585,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597958195,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597972014,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541625,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:cpu_latency_qos_remove_request",
        "kernel/power/qos.c:pm_qos_update_flags",
        "kernel/power/qos.c:pm_qos_update_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580552255,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580556790,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580561519,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621841959,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:printk_sprint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580643455,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu",
        "kernel/irq/handle.c:__handle_irq_event_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580671221,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722243,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/matrix.c:irq_matrix_free",
        "kernel/irq/matrix.c:irq_matrix_alloc",
        "kernel/irq/matrix.c:irq_matrix_remove_reserved",
        "kernel/irq/matrix.c:irq_matrix_reserve",
        "kernel/irq/matrix.c:irq_matrix_assign",
        "kernel/irq/matrix.c:irq_matrix_alloc_managed",
        "kernel/irq/matrix.c:irq_matrix_remove_managed",
        "kernel/irq/matrix.c:irq_matrix_reserve_managed",
        "kernel/irq/matrix.c:irq_matrix_assign_system",
        "kernel/irq/matrix.c:irq_matrix_offline",
        "kernel/irq/matrix.c:irq_matrix_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731225,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:show_stalled_task_trace",
        "kernel/rcu/update.c:trc_check_slow_task",
        "kernel/rcu/update.c:trc_inspect_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580776963,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_nocb_cpu_offload",
        "kernel/rcu/tree.c:rcu_nocb_cpu_deoffload",
        "kernel/rcu/tree.c:rcu_nocb_rdp_deoffload",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:rcu_check_gp_kthread_starvation",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/rcu/tree.c:__call_rcu_common",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580839301,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580867386,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871806,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900811,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module",
        "kernel/module/main.c:module_put",
        "kernel/module/main.c:try_module_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906928,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/module/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954333,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:timer_clear_idle",
        "kernel/time/timer.c:get_next_timer_interrupt",
        "kernel/time/timer.c:get_next_timer_interrupt",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:detach_if_pending",
        "kernel/time/timer.c:enqueue_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964342,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_cpu_dying",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:enqueue_hrtimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999501,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_fired"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020581,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035574,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:it_real_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045944,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056600,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:can_stop_idle_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:check_tick_dependency",
        "kernel/time/tick-sched.c:check_tick_dependency",
        "kernel/time/tick-sched.c:check_tick_dependency",
        "kernel/time/tick-sched.c:check_tick_dependency",
        "kernel/time/tick-sched.c:check_tick_dependency",
        "kernel/time/tick-sched.c:check_tick_dependency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094972,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_on_cpu",
        "kernel/smp.c:wake_up_all_idle_cpus",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_single",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:__flush_smp_call_function_queue",
        "kernel/smp.c:generic_exec_single",
        "kernel/smp.c:generic_exec_single",
        "kernel/smp.c:generic_exec_single",
        "kernel/smp.c:__smp_call_single_queue",
        "kernel/smp.c:__smp_call_single_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189707,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581212630,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215933,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581412315,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_per_cpu",
        "kernel/debug/kdb/kdb_main.c:kdb_cpu_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426953,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581433275,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539812,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675345,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:trace_sched_switch_callback",
        "kernel/trace/trace_osnoise.c:trace_softirq_exit_callback",
        "kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit",
        "kernel/trace/trace_osnoise.c:trace_osnoise_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820826,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:action_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581883068,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_vprintk",
        "kernel/trace/bpf_trace.c:bpf_trace_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940360,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/trace/trace_kdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kdb.c:kdb_ftdump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581998279,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/trace/rv/monitors/wwnr/wwnr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr",
        "kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582003441,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq_work.c:irq_work_needs_cpu",
        "kernel/irq_work.c:irq_work_queue_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582474427,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_generic_redirect",
        "kernel/bpf/devmap.c:bq_xmit_all",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582481831,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_generic_redirect",
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597868454,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/context_tracking.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/context_tracking.c:__ct_user_exit",
        "kernel/context_tracking.c:__ct_user_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582720614,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:rseq_ip_fixup",
        "kernel/rseq.c:rseq_update_cpu_node_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736865,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:__filemap_set_wb_err",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774407,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:wake_oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582790330,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_wait_writeback_killable",
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:domain_dirty_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582820571,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582917488,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:scan_folios",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:reclaim_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925037,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/shrinker.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shrinker.c:do_shrink_slab",
        "mm/shrinker.c:do_shrink_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583000546,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_register_va"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583013165,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_setup_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067848,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:compaction_defer_reset",
        "mm/compaction.c:compaction_deferred",
        "mm/compaction.c:defer_compaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583119929,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:__mmap_lock_do_trace_released",
        "mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned",
        "mm/mmap_lock.c:__mmap_lock_do_trace_start_locking"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583151029,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:set_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583190069,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_drain_remote"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583214132,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:vm_unmapped_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583279697,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583291271,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583360943,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcppages_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583405443,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmalloc_node_trace",
        "mm/slub.c:kmalloc_trace",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:kmalloc_large",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583639317,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:__ksm_enter",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:scan_time_advisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583652615,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/kfence/report.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/report.c:kfence_report_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583671470,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730697,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583755497,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583824184,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583843995,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:action_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583869341,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584001961,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_binprm",
        "fs/exec.c:__set_task_comm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584131096,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584264903,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_do_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:write_inode",
        "fs/fs-writeback.c:write_inode",
        "fs/fs-writeback.c:queue_io",
        "fs/fs-writeback.c:sb_clear_inode_writeback",
        "fs/fs-writeback.c:sb_mark_inode_writeback",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:wb_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584338126,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:mark_buffer_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584508445,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_insert_pfn_mkwrite",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_pmd_load_hole",
        "fs/dax.c:dax_pmd_load_hole",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584583217,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_posix",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:generic_setlease",
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:leases_conflict",
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584652343,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/iomap/iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/iter.c:iomap_iter",
        "fs/iomap/iter.c:iomap_iter_done",
        "fs/iomap/iter.c:iomap_iter_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584663115,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_release_folio",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584673950,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584772551,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584807880,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/proc/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:get_iowait_time",
        "fs/proc/stat.c:get_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584910028,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584922868,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584952464,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_ext_rm_idx",
        "fs/ext4/extents.c:__read_extent_tree_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584981287,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_scan",
        "fs/ext4/extents_status.c:ext4_es_count",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584993123,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_logdev",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper",
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584994829,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585006462,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585018444,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585075914,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_update_other_inode_time",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_release_folio",
        "fs/ext4/inode.c:__ext4_journalled_invalidate_folio",
        "fs/ext4/inode.c:ext4_invalidate_folio",
        "fs/ext4/inode.c:ext4_read_folio",
        "fs/ext4/inode.c:ext4_alloc_da_blocks",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_reserve_space",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585096809,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_getfsmap_format",
        "fs/ext4/ioctl.c:ext4_force_shutdown",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585135483,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_collect_stats",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585209764,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_unlink",
        "fs/ext4/namei.c:ext4_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585335916,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_nfs_commit_metadata",
        "fs/ext4/super.c:ext4_drop_inode",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585432570,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/ext4/fast_commit.c:ext4_fc_cleanup",
        "fs/ext4/fast_commit.c:ext4_fc_commit",
        "fs/ext4/fast_commit.c:ext4_fc_update_stats",
        "fs/ext4/fast_commit.c:ext4_fc_track_range",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode",
        "fs/ext4/fast_commit.c:__ext4_fc_track_create",
        "fs/ext4/fast_commit.c:__ext4_fc_track_link",
        "fs/ext4/fast_commit.c:__ext4_fc_track_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585454831,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_start_reserved",
        "fs/jbd2/transaction.c:jbd2__journal_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585464828,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585476465,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585505405,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_shrink_count",
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan",
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586057518,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_audit_post_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586891887,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586923642,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:submit_bio_noacct",
        "block/blk-core.c:submit_bio_noacct_nocheck"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959943,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:bio_attempt_back_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:__bio_split_to_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586995186,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-mq.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_add_rq_to_plug",
        "block/blk-mq.c:blk_add_rq_to_plug",
        "block/blk-mq.c:blk_mq_start_request",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_account_io_done",
        "block/blk-mq.c:blk_update_request",
        "block/blk-mq.c:blk_update_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587186147,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587201116,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587230695,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:rwb_trace_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587326838,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_submit_fail_init",
        "io_uring/io_uring.c:io_file_get_normal",
        "io_uring/io_uring.c:io_drain_req",
        "io_uring/io_uring.c:__io_submit_flush_completions",
        "io_uring/io_uring.c:__io_run_local_work",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:io_fill_cqe_aux",
        "io_uring/io_uring.c:io_cqring_event_overflow",
        "io_uring/io_uring.c:io_queue_iowq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587359065,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "io_uring/timeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_disarm_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587365630,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_offload_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377416,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:io_arm_poll_handler",
        "io_uring/poll.c:__io_poll_execute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587405344,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587413859,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "io_uring/register.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/register.c:__do_sys_io_uring_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588481117,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:do_trace_rdpmc",
        "arch/x86/lib/msr.c:do_trace_read_msr",
        "arch/x86/lib/msr.c:do_trace_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588588260,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit",
        "drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588652753,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:__pwm_apply",
        "drivers/pwm/core.c:pwm_device_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588841788,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:pci_print_aer",
        "drivers/pci/pcie/aer.c:aer_print_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589229936,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589762693,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589909267,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_duty_cycle_nolock",
        "drivers/clk/clk.c:clk_core_set_phase_nolock",
        "drivers/clk/clk.c:clk_core_set_phase_nolock",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_calc_new_rates",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_round_rate",
        "drivers/clk/clk.c:clk_hw_round_rate",
        "drivers/clk/clk.c:clk_hw_round_rate",
        "drivers/clk/clk.c:clk_core_round_rate_nolock",
        "drivers/clk/clk.c:clk_core_round_rate_nolock",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_unprepare_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_prepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590063385,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590114327,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590169085,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214111,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:regulator_allow_bypass",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590767975,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:qi_submit_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590822868,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590856994,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:report_iommu_fault",
        "drivers/iommu/iommu.c:__iommu_unmap",
        "drivers/iommu/iommu.c:__iommu_map",
        "drivers/iommu/iommu.c:iommu_group_alloc_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590883657,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590976333,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590994747,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/base/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/cpu.c:register_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591001143,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/base/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:__devm_add_action",
        "drivers/base/devres.c:devres_remove_group",
        "drivers/base/devres.c:devres_close_group",
        "drivers/base/devres.c:devres_open_group",
        "drivers/base/devres.c:release_nodes",
        "drivers/base/devres.c:devres_remove",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591054741,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/base/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/qos.c:__dev_pm_qos_remove_request",
        "drivers/base/power/qos.c:__dev_pm_qos_update_request",
        "drivers/base/power/qos.c:__dev_pm_qos_add_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591067968,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591091042,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591095819,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591154348,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_async_complete_cb",
        "drivers/base/regmap/regmap.c:regmap_bulk_read",
        "drivers/base/regmap/regmap.c:_regmap_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_read",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write",
        "drivers/base/regmap/regmap.c:regmap_bulk_write",
        "drivers/base/regmap/regmap.c:_regmap_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_bus_formatted_write",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591178770,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/base/regmap/regcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache.c:regcache_cache_bypass",
        "drivers/base/regmap/regcache.c:regcache_cache_only",
        "drivers/base/regmap/regcache.c:regcache_drop_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591510334,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked",
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591535289,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591576795,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591596997,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_done_internal",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd",
        "drivers/scsi/scsi_lib.c:scsi_dispatch_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591698797,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591773329,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591847113,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_done",
        "drivers/ata/libata-eh.c:ata_eh_about_to_do",
        "drivers/ata/libata-eh.c:ata_eh_thaw_port",
        "drivers/ata/libata-eh.c:__ata_port_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591882008,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_port_intr",
        "drivers/ata/libata-sff.c:ata_bmdma_port_intr",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:__ata_sff_port_intr",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_tf_to_host",
        "drivers/ata/libata-sff.c:ata_tf_to_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591909275,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/ata/ata_piix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/ata_piix.c:piix_irq_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592176054,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/gpu/drm/drm_vblank.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_vblank.c:drm_handle_vblank_events",
        "drivers/gpu/drm/drm_vblank.c:drm_queue_vblank_event",
        "drivers/gpu/drm/drm_vblank.c:send_vblank_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592347210,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/spi/spi.c:__spi_pump_transfer_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592425137,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_c45_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_c45_read",
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592452898,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_act"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592498669,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "drivers/net/virtio_net.c:virtnet_xdp_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592616214,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593109904,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593126974,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev",
        "drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_free_virt_device",
        "drivers/usb/host/xhci-mem.c:xhci_ring_expansion",
        "drivers/usb/host/xhci-mem.c:xhci_ring_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593142093,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:queue_trb",
        "drivers/usb/host/xhci-ring.c:xhci_handle_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell",
        "drivers/usb/host/xhci-ring.c:inc_enq",
        "drivers/usb/host/xhci-ring.c:inc_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593184042,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593215156,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx",
        "drivers/usb/host/xhci-dbgcap.c:dbc_free_request",
        "drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593372411,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_set_offset",
        "drivers/rtc/interface.c:rtc_read_offset",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_alarm_disable",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:rtc_initialize_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593405936,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593421703,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593502627,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/hwmon/hwmon.c:hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:hwmon_attr_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593516105,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593537635,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_helpers.c:__thermal_cdev_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593547478,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/thermal/gov_fair_share.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_fair_share.c:fair_share_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593548917,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/thermal/gov_step_wise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_step_wise.c:thermal_zone_trip_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593554693,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:pid_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593559567,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593560859,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count",
        "drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593569903,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/watchdog/watchdog_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593578874,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593597975,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_submit_discard_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593721715,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_submit_bio_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593786483,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593793358,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593857340,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_notify_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593896212,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593928986,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597870676,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593953210,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/cpuidle/governors/haltpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593962064,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_cqe_request_done",
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594136715,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594200718,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/devfreq.c:devfreq_set_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594241369,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/ras/ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/ras.c:log_arm_hw_error",
        "drivers/ras/ras.c:log_non_standard_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594264370,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "drivers/interconnect/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594302813,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:call_trace_sock_recv_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594336011,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:sk_error_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594428590,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "net/core/skbuff.c:kfree_skb_reason",
        "net/core/skbuff.c:kfree_skb_reason"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594430235,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594568902,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:net_rps_send_ipi",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_qdisc_enqueue",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:dev_hard_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594618723,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594783741,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect_frame",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594805464,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_rxq_info_reg_mem_model",
        "net/core/xdp.c:mem_allocator_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594821719,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_frags",
        "net/core/gro.c:napi_gro_receive",
        "net/core/gro.c:napi_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594850885,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_update_nid",
        "net/core/page_pool.c:page_pool_return_page",
        "net/core/page_pool.c:page_pool_inflight",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594862570,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594866534,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:poll_one_napi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594983998,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_data_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595031110,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:__qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_reset",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dequeue_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595051352,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595121977,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:do_trace_netlink_extack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595174785,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595504908,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595515689,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_rtx_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595586889,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595599544,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_ca_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595659922,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595737158,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_sk_state_store",
        "net/ipv4/af_inet.c:inet_sk_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595810342,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595936996,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv4/tcp_sigpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596099682,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/xfrm/espintcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/espintcp.c:espintcp_data_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596272925,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:fib6_table_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596372321,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596463863,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596752367,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/devlink/health.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_health_report",
        "net/devlink/health.c:devlink_health_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596755208,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/devlink/trap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/trap.c:devlink_trap_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596972457,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597003329,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_data_ready",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597012707,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/mptcp/options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:ack_update_msk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597079638,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597093507,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_route_input",
        "net/mctp/route.c:__mctp_key_done_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597099148,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/handshake/alert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/alert.c:tls_alert_recv",
        "net/handshake/alert.c:tls_alert_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597101505,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/handshake/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/netlink.c:handshake_nl_done_doit",
        "net/handshake/netlink.c:handshake_nl_done_doit",
        "net/handshake/netlink.c:handshake_nl_accept_doit",
        "net/handshake/netlink.c:handshake_nl_accept_doit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597105460,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "net/handshake/request.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_req_cancel",
        "net/handshake/request.c:handshake_complete",
        "net/handshake/request.c:handshake_req_submit",
        "net/handshake/request.c:handshake_req_submit",
        "net/handshake/request.c:handshake_req_submit",
        "net/handshake/request.c:handshake_sk_destruct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597252335,
      "name": "cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:1102",
      "file": "lib/maple_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/maple_tree.c:mt_find",
        "lib/maple_tree.c:mtree_erase",
        "lib/maple_tree.c:mtree_store_range",
        "lib/maple_tree.c:mtree_load",
        "lib/maple_tree.c:mas_store_prealloc",
        "lib/maple_tree.c:mas_store_gfp",
        "lib/maple_tree.c:mas_store",
        "lib/maple_tree.c:mas_wr_bnode",
        "lib/maple_tree.c:mas_wr_append",
        "lib/maple_tree.c:mas_wr_slot_store",
        "lib/maple_tree.c:mas_wr_walk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911712,
      "name": "cpu_online",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool cpu_online(unsigned int cpu)
```
</details>
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

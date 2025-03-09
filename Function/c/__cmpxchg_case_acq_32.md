# Function: <code>__cmpxchg_case_acq_32</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 __cmpxchg_case_acq_32(volatile void * ptr, u32 old, u32 new)
```

```json
{
  "name": "__cmpxchg_case_acq_32",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510804472,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:kernel_init_freeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490183336,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "arch/arm64/kernel/debug-monitors.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/debug-monitors.c:register_kernel_break_hook",
        "arch/arm64/kernel/debug-monitors.c:register_user_break_hook",
        "arch/arm64/kernel/debug-monitors.c:register_kernel_step_hook",
        "arch/arm64/kernel/debug-monitors.c:register_user_step_hook",
        "arch/arm64/kernel/debug-monitors.c:unregister_debug_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490239248,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/traps.c:call_undef_hook",
        "arch/arm64/kernel/traps.c:unregister_undef_hook",
        "arch/arm64/kernel/traps.c:register_undef_hook",
        "arch/arm64/kernel/traps.c:die"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503948780,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "arch/arm64/kernel/insn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/insn.c:__aarch64_insn_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490256520,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "arch/arm64/kernel/cpu_errata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490261692,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "arch/arm64/kernel/cpufeature.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490305036,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "arch/arm64/kernel/perf_event.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/perf_event.c:armv8pmu_stop",
        "arch/arm64/kernel/perf_event.c:armv8pmu_start",
        "arch/arm64/kernel/perf_event.c:armv8pmu_disable_event",
        "arch/arm64/kernel/perf_event.c:armv8pmu_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490321400,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "arch/arm64/kernel/armv8_deprecated.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/armv8_deprecated.c:run_all_insn_set_hw_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490346192,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:set_swapper_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490351328,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "arch/arm64/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/context.c:check_and_switch_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490386452,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:hardware_disable_all",
        "virt/kvm/kvm_main.c:kvm_dying_cpu",
        "virt/kvm/kvm_main.c:kvm_starting_cpu",
        "virt/kvm/kvm_main.c:kvm_clear_dirty_log_protect",
        "virt/kvm/kvm_main.c:kvm_get_dirty_log_protect",
        "virt/kvm/kvm_main.c:kvm_create_vm",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_test_young",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_young",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_flush_young",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_invalidate_range_start",
        "virt/kvm/kvm_main.c:kvm_mmu_notifier_change_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490417912,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/coalesced_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/coalesced_mmio.c:coalesced_mmio_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490424644,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/eventfd.c:kvm_irq_routing_update",
        "virt/kvm/eventfd.c:kvm_irqfd_release",
        "virt/kvm/eventfd.c:kvm_irqfd",
        "virt/kvm/eventfd.c:kvm_irqfd_assign",
        "virt/kvm/eventfd.c:irqfd_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490446060,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490471740,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:kvm_arch_flush_shadow_memslot",
        "virt/kvm/arm/mmu.c:kvm_arch_prepare_memory_region",
        "virt/kvm/arm/mmu.c:kvm_handle_guest_abort",
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:kvm_mmu_wp_memory_region",
        "virt/kvm/arm/mmu.c:kvm_phys_addr_ioremap",
        "virt/kvm/arm/mmu.c:kvm_free_stage2_pgd",
        "virt/kvm/arm/mmu.c:stage2_unmap_vm",
        "virt/kvm/arm/mmu.c:stage2_flush_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490538336,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/arm/vgic/vgic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_is_active",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_set_owner",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_unmap_phys_irq",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_reset_mapped_irq",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_phys_irq",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq",
        "virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock",
        "virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock",
        "virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock",
        "virt/kvm/arm/vgic/vgic.c:vgic_irq_cmp",
        "virt/kvm/arm/vgic/vgic.c:vgic_irq_cmp",
        "virt/kvm/arm/vgic/vgic.c:vgic_flush_pending_lpis",
        "virt/kvm/arm/vgic/vgic.c:vgic_flush_pending_lpis"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490543480,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/arm/vgic/vgic-v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_fold_lr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490547896,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/arm/vgic/vgic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_fold_lr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490558620,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/arm/vgic/vgic-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_write_irq_line_level_info",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_config",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_priority",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cpending",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_pending",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cenable",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490563040,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/arm/vgic/vgic-mmio-v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipends",
        "virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipendc",
        "virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_target",
        "virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490569440,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/arm/vgic/vgic-mmio-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi",
        "virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_uaccess_write_pending",
        "virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_write_irouter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490593744,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/arm/vgic/vgic-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_trigger_msi",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_invalidate_cache",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_copy_lpi_list",
        "virt/kvm/arm/vgic/vgic-its.c:update_lpi_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490596000,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "virt/kvm/arm/vgic/vgic-debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-debug.c:vgic_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490616176,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "arch/arm/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/xen/p2m.c:__set_phys_to_machine_multi",
        "arch/arm/xen/p2m.c:__set_phys_to_machine_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490637716,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:mm_release",
        "kernel/fork.c:get_task_mm",
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490639916,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490661356,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490683124,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:__release_region",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:adjust_resource",
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:insert_resource_expand_to_fit",
        "kernel/resource.c:insert_resource_conflict",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource",
        "kernel/resource.c:request_resource_conflict",
        "kernel/resource.c:release_child_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490718524,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_may_access",
        "kernel/ptrace.c:ptrace_check_attach",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490722488,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490760832,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:do_sigpending",
        "kernel/signal.c:__set_current_blocked",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:sigqueue_free",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:__lock_task_sighand",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:flush_itimer_signals",
        "kernel/signal.c:flush_signals",
        "kernel/signal.c:calculate_sigpending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490770060,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_auxv",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__arm64_sys_setpgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490791220,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/umh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/umh.c:call_usermodehelper_exec_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490822820,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:work_busy",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:pwq_adjust_max_active",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:drain_workqueue",
        "kernel/workqueue.c:flush_workqueue_prep_pwqs",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:pool_mayday_timeout",
        "kernel/workqueue.c:pool_mayday_timeout",
        "kernel/workqueue.c:idle_worker_timeout",
        "kernel/workqueue.c:create_worker",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_sleeping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490830328,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:disable_pid_allocation",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490831400,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_run",
        "kernel/task_work.c:task_work_cancel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490838056,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_charp",
        "kernel/params.c:maybe_kfree_parameter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490847232,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node",
        "kernel/kthread.c:__kthread_parkme"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490858116,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:switch_task_namespaces"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490860980,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/notifier.c:atomic_notifier_chain_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490869920,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/async.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/async.c:async_unregister_domain",
        "kernel/async.c:async_schedule_node_domain",
        "kernel/async.c:async_schedule_node_domain",
        "kernel/async.c:async_run_entry_fn",
        "kernel/async.c:lowest_in_progress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490877016,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/ucount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:put_ucounts",
        "kernel/ucount.c:get_ucounts",
        "kernel/ucount.c:get_ucounts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490911664,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/sched/core.c:cpu_cgroup_can_attach",
        "kernel/sched/core.c:sched_offline_group",
        "kernel/sched/core.c:sched_online_group",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:__balance_callback",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:task_rq_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490939564,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust",
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490940940,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:dequeue_task_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490997288,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:rq_online_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_slack_timer",
        "kernel/sched/fair.c:sched_cfs_slack_timer",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/fair.c:remove_entity_load_avg",
        "kernel/sched/fair.c:task_numa_free",
        "kernel/sched/fair.c:task_numa_placement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491004140,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:tg_set_rt_bandwidth",
        "kernel/sched/rt.c:tg_set_rt_bandwidth",
        "kernel/sched/rt.c:tg_set_rt_bandwidth",
        "kernel/sched/rt.c:tg_set_rt_bandwidth",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:rq_online_rt",
        "kernel/sched/rt.c:rq_online_rt",
        "kernel/sched/rt.c:rq_online_rt",
        "kernel/sched/rt.c:rq_online_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func",
        "kernel/sched/rt.c:rto_push_irq_work_func",
        "kernel/sched/rt.c:rto_push_irq_work_func",
        "kernel/sched/rt.c:rto_push_irq_work_func",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491038960,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_cpu_busy",
        "kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink",
        "kernel/sched/deadline.c:dl_task_can_attach",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:sched_dl_do_global",
        "kernel/sched/deadline.c:sched_dl_global_validate",
        "kernel/sched/deadline.c:dl_clear_root_domain",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:set_cpus_allowed_dl",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:init_dl_bw",
        "kernel/sched/deadline.c:task_non_contending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491043988,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:finish_wait",
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event",
        "kernel/sched/wait.c:prepare_to_wait_exclusive",
        "kernel/sched/wait.c:prepare_to_wait",
        "kernel/sched/wait.c:__wake_up_common_lock",
        "kernel/sched/wait.c:remove_wait_queue",
        "kernel/sched/wait.c:add_wait_queue_exclusive",
        "kernel/sched/wait.c:add_wait_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491046948,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:finish_swait",
        "kernel/sched/swait.c:prepare_to_swait_event",
        "kernel/sched/swait.c:prepare_to_swait_exclusive",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503928900,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:__wait_for_common",
        "kernel/sched/completion.c:__wait_for_common",
        "kernel/sched/completion.c:complete_all",
        "kernel/sched/completion.c:complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491050640,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_set",
        "kernel/sched/cpudeadline.c:cpudl_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491053604,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491086096,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:print_cpu",
        "kernel/sched/debug.c:print_cfs_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491095044,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_work",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491104360,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503935628,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503937304,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/locking/semaphore.c:up",
        "kernel/locking/semaphore.c:down_timeout",
        "kernel/locking/semaphore.c:down_trylock",
        "kernel/locking/semaphore.c:down_killable",
        "kernel/locking/semaphore.c:down_interruptible",
        "kernel/locking/semaphore.c:down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491112180,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
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
      "addr": 18446603336503948232,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_write_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491116600,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/locking/osq_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491116920,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491123800,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491124864,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/locking/qrwlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_write_lock_slowpath",
        "kernel/locking/qrwlock.c:queued_read_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491126140,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:pm_qos_power_read",
        "kernel/power/qos.c:pm_qos_update_flags",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491140336,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491144916,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:__wakelocks_gc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491151300,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/printk/printk.c:kmsg_dump_register",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491167828,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:__printk_safe_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491171300,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:actions_show",
        "kernel/irq/irqdesc.c:name_show",
        "kernel/irq/irqdesc.c:wakeup_show",
        "kernel/irq/irqdesc.c:type_show",
        "kernel/irq/irqdesc.c:hwirq_show",
        "kernel/irq/irqdesc.c:chip_name_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491174400,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:handle_irq_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491189800,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__free_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:free_nmi",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:irq_wake_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_notifier",
        "kernel/irq/manage.c:irq_affinity_notify",
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/manage.c:__synchronize_hardirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491193324,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:__report_bad_irq",
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/spurious.c:irq_wait_for_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491199560,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_fasteoi_mask_irq",
        "kernel/irq/chip.c:handle_fasteoi_ack_irq",
        "kernel/irq/chip.c:irq_cpu_offline",
        "kernel/irq/chip.c:irq_cpu_online",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_untracked_irq",
        "kernel/irq/chip.c:handle_untracked_irq",
        "kernel/irq/chip.c:handle_simple_irq",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:handle_nested_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491211112,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips",
        "kernel/irq/generic-chip.c:irq_gc_set_wake",
        "kernel/irq/generic-chip.c:irq_gc_eoi",
        "kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set",
        "kernel/irq/generic-chip.c:irq_gc_ack_clr_bit",
        "kernel/irq/generic-chip.c:irq_gc_ack_set_bit",
        "kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg",
        "kernel/irq/generic-chip.c:irq_gc_mask_clr_bit",
        "kernel/irq/generic-chip.c:irq_gc_mask_set_bit",
        "kernel/irq/generic-chip.c:irq_gc_mask_disable_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491213668,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/irq/autoprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491229068,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:show_interrupts",
        "kernel/irq/proc.c:register_handler_proc",
        "kernel/irq/proc.c:irq_affinity_hint_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491230620,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491231052,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/irq/pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/pm.c:resume_irqs",
        "kernel/irq/pm.c:suspend_device_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491240460,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491243008,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/rcu/sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/sync.c:rcu_sync_dtor",
        "kernel/rcu/sync.c:rcu_sync_exit",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/sync.c:rcu_sync_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491248188,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491269408,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult",
        "kernel/rcu/tree.c:sync_rcu_preempt_exp_done_unlocked",
        "kernel/rcu/tree.c:rcu_iw_handler",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_report_dead",
        "kernel/rcu/tree.c:rcu_report_dead",
        "kernel/rcu/tree.c:rcu_report_dead",
        "kernel/rcu/tree.c:rcu_cpu_starting",
        "kernel/rcu/tree.c:rcutree_offline_cpu",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491293144,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/dma/coherent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/coherent.c:__dma_release_from_coherent",
        "kernel/dma/coherent.c:__dma_alloc_from_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491297888,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491301536,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:kcmp_epoll_target",
        "kernel/kcmp.c:get_file_raw_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491303480,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491336360,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:get_next_timer_interrupt",
        "kernel/time/timer.c:add_timer_on",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:lock_timer_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491345832,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/hrtimer.c:lock_hrtimer_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491358516,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:change_clocksource",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier",
        "kernel/time/timekeeping.c:pvclock_gtod_register_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491367348,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_active_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491374968,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_handle_timer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "kernel/time/alarmtimer.c:alarmtimer_get_rtcdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491387492,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__arm64_sys_timer_delete",
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/time/posix-timers.c:posix_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491395164,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers",
        "kernel/time/posix-cpu-timers.c:update_rlimit_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491400672,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491403748,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:sysfs_show_current_tick_dev",
        "kernel/time/clockevents.c:tick_cleanup_dead_cpu",
        "kernel/time/clockevents.c:tick_offline_cpu",
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491409948,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_periodic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491416952,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull",
        "kernel/time/tick-broadcast.c:tick_broadcast_switch_to_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_resume_broadcast",
        "kernel/time/tick-broadcast.c:tick_suspend_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_update_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491420516,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_init_jiffy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491428940,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_cleanup_begin",
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491499764,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect",
        "kernel/acct.c:do_acct_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491567288,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_free",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_task_iter_end",
        "kernel/cgroup/cgroup.c:css_task_iter_next",
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_migrate",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup.c:cgroup_task_count",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/cgroup/cgroup.c:cgroup_idr_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491571924,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/cgroup/rstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_locked",
        "kernel/cgroup/rstat.c:cgroup_rstat_updated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491573132,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:cgroupns_get",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491582800,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_show_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491588356,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_leave_frozen",
        "kernel/cgroup/freezer.c:cgroup_leave_frozen",
        "kernel/cgroup/freezer.c:cgroup_enter_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491616520,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump",
        "kernel/cgroup/cpuset.c:__cpuset_node_allowed",
        "kernel/cgroup/cpuset.c:cpuset_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_bind",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_read_u64",
        "kernel/cgroup/cpuset.c:cpuset_common_seq_show",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491618588,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:utsns_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491627948,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491630576,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:cpu_stopper_thread",
        "kernel/stop_machine.c:cpu_stop_should_run",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491637520,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_end",
        "kernel/audit.c:audit_get_tty",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491671468,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_getname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491688208,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_tag_tree",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:audit_trim_trees",
        "kernel/audit_tree.c:audit_remove_tree_rule",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks",
        "kernel/audit_tree.c:prune_tree_chunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491697224,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:pre_handler_kretprobe",
        "kernel/kprobes.c:pre_handler_kretprobe",
        "kernel/kprobes.c:pre_handler_kretprobe",
        "kernel/kprobes.c:cleanup_rp_inst",
        "kernel/kprobes.c:kprobe_flush_task",
        "kernel/kprobes.c:kretprobe_hash_lock",
        "kernel/kprobes.c:recycle_rp_inst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491704900,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491744808,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491768012,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491781184,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/delayacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/delayacct.c:__delayacct_blkio_ticks",
        "kernel/delayacct.c:__delayacct_add_tsk",
        "kernel/delayacct.c:delayacct_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491784792,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491790280,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock_global"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491830784,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_read_page",
        "kernel/trace/ring_buffer.c:ring_buffer_free_read_page",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read",
        "kernel/trace/ring_buffer.c:ring_buffer_read_finish",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_iter_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491868324,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:saved_cmdlines_start",
        "kernel/trace/trace.c:trace_find_cmdline",
        "kernel/trace/trace.c:tracing_stop",
        "kernel/trace/trace.c:tracing_snapshot_cond_disable",
        "kernel/trace/trace.c:tracing_cond_snapshot_data"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:tracing_release",
        "kernel/trace/trace.c:__tracing_open",
        "kernel/trace/trace.c:tracing_stop",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable"
      ]
    },
    {
      "addr": 18446603336491927320,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:wakeup_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491934516,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/trace/trace_stack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_stack.c:t_start",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_stack.c:stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491954924,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491968928,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:remove_event_file_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492094644,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492114404,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492143884,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492214756,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:bpf_spin_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492224664,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492237104,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492240592,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_push_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_push_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492244736,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:trie_delete_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492250396,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_link",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_release",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_assign",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492251352,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_push_elem",
        "kernel/bpf/queue_stack_maps.c:__stack_map_get",
        "kernel/bpf/queue_stack_maps.c:__queue_map_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492275240,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492282348,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_notification",
        "kernel/bpf/devmap.c:dev_map_hash_update_elem",
        "kernel/bpf/devmap.c:dev_map_hash_delete_elem",
        "kernel/bpf/devmap.c:dev_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492287120,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492291628,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_try_sock_delete",
        "kernel/bpf/xskmap.c:xsk_map_delete_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_update_elem",
        "kernel/bpf/xskmap.c:xsk_map_sock_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492320792,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/bpf/reuseport_array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_delete_elem",
        "kernel/bpf/reuseport_array.c:reuseport_array_delete_elem",
        "kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492388580,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_free_task",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/core.c:perf_event_mmap",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:ring_buffer_attach",
        "kernel/events/core.c:ring_buffer_attach",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_install_in_context",
        "kernel/events/core.c:perf_unpin_context",
        "kernel/events/core.c:perf_lock_task_context",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:event_function_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492417012,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:vma_has_uprobes",
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:__uprobe_unregister",
        "kernel/events/uprobes.c:find_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492424972,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_serial_worker",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_reorder",
        "kernel/padata.c:padata_find_next",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_parallel_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492445548,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/filemap.c:wake_up_page_bit",
        "mm/filemap.c:wake_up_page_bit",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:__filemap_fdatawrite_range",
        "mm/filemap.c:delete_from_page_cache_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492472316,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_free",
        "mm/mempool.c:mempool_alloc",
        "mm/mempool.c:mempool_resize",
        "mm/mempool.c:mempool_resize",
        "mm/mempool.c:mempool_resize",
        "mm/mempool.c:mempool_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492481320,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:find_lock_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492486772,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/fadvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise",
        "mm/fadvise.c:generic_fadvise"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492498988,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:domain_update_bandwidth",
        "mm/page-writeback.c:bdi_set_max_ratio",
        "mm/page-writeback.c:bdi_set_min_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492521488,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492531484,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492574300,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:__remove_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492584828,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_inode",
        "mm/shmem.c:shmem_lock",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_getattr",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_free_swap",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_free_inode",
        "mm/shmem.c:shmem_reserve_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492618148,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:get_cmdline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492623444,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showfree_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492642112,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_put",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:bdi_get_by_id",
        "mm/backing-dev.c:wb_blkcg_offline",
        "mm/backing-dev.c:wb_memcg_offline",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_congested_get_create",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "mm/backing-dev.c:bdi_debug_stats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492645996,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:unuse_mm",
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492657952,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492668964,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_destroy",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:kmemcg_cache_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492697204,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492710556,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:memcg_update_all_list_lrus",
        "mm/list_lru.c:list_lru_walk_node",
        "mm/list_lru.c:list_lru_walk_one_irq",
        "mm/list_lru.c:list_lru_walk_one",
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492711964,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492720100,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492729856,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492765172,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492772872,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:user_shm_unlock",
        "mm/mlock.c:user_shm_lock",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492788272,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492798228,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492802248,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492806932,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492819440,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492829528,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:s_start",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:__get_vm_area_node",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus",
        "mm/vmalloc.c:find_vmap_area",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:alloc_vmap_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492887076,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:set_hwpoison_free_buddy_page",
        "mm/page_alloc.c:is_free_buddy_page",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492888844,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492903044,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492913980,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492944580,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:si_swapinfo",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:has_usable_swap",
        "mm/swapfile.c:enable_swap_info",
        "mm/swapfile.c:enable_swap_info",
        "mm/swapfile.c:enable_swap_info",
        "mm/swapfile.c:enable_swap_info",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:page_swapcount",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:put_swap_page",
        "mm/swapfile.c:get_swap_page_of_type",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:add_to_avail_list",
        "mm/swapfile.c:scan_swap_map_try_ssd_cluster",
        "mm/swapfile.c:swap_discard_work",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:swap_do_scheduled_discard"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492948656,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:free_swap_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492950044,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_curr_pages",
        "mm/frontswap.c:frontswap_shrink",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492955464,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_invalidate_area",
        "mm/zswap.c:zswap_frontswap_invalidate_page",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_pool_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492962144,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "mm/dmapool.c:dma_pool_alloc",
        "mm/dmapool.c:show_pools"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492999476,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:isolate_huge_page",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_overcommit_handler",
        "mm/hugetlb.c:nr_overcommit_hugepages_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__vma_reservation_common",
        "mm/hugetlb.c:__vma_reservation_common",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:alloc_surplus_huge_page",
        "mm/hugetlb.c:prep_new_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:alloc_gigantic_page",
        "mm/hugetlb.c:alloc_gigantic_page",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:region_chg",
        "mm/hugetlb.c:region_chg",
        "mm/hugetlb.c:region_add",
        "mm/hugetlb.c:hugepage_put_subpool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493022772,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_free_shared_policy",
        "mm/mempolicy.c:mpol_set_shared_policy",
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:mpol_put_task_policy",
        "mm/mempolicy.c:__mpol_dup",
        "mm/mempolicy.c:mempolicy_nodemask_intersects",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493027060,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/mmu_notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_notifier.c:mmu_notifier_put",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:mmu_notifier_get_locked",
        "mm/mmu_notifier.c:__mmu_notifier_register",
        "mm/mmu_notifier.c:__mmu_notifier_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493038148,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:run_store",
        "mm/ksm.c:run_store",
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:__ksm_enter",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493078216,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:__slab_free",
        "mm/slub.c:count_partial",
        "mm/slub.c:free_debug_processing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503906404,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493117140,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:__migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493144792,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:free_transhuge_page",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493168736,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__khugepaged_exit",
        "mm/khugepaged.c:__khugepaged_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493194872,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_clear_mc",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_oom_unregister_event",
        "mm/memcontrol.c:mem_cgroup_oom_register_event",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493221372,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure",
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493222968,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_record",
        "mm/swap_cgroup.c:swap_cgroup_cmpxchg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493226308,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493238564,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_work_func",
        "mm/memory-failure.c:memory_failure_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493244532,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493246796,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/zpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zpool.c:zpool_destroy_pool",
        "mm/zpool.c:zpool_create_pool",
        "mm/zpool.c:zpool_get_driver",
        "mm/zpool.c:zpool_unregister_driver",
        "mm/zpool.c:zpool_register_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493249560,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_reclaim_page",
        "mm/zbud.c:zbud_reclaim_page",
        "mm/zbud.c:zbud_free",
        "mm/zbud.c:zbud_alloc",
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493254632,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493266576,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_putback",
        "mm/balloon_compaction.c:balloon_page_isolate",
        "mm/balloon_compaction.c:balloon_page_enqueue",
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_list_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493272160,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493273460,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493281272,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_unregister",
        "mm/hmm.c:hmm_range_register",
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_invalidate_range_start",
        "mm/hmm.c:notifiers_decrement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493285064,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493300212,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493336532,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:user_get_super",
        "fs/super.c:user_get_super",
        "fs/super.c:get_active_super",
        "fs/super.c:__get_super_thawed",
        "fs/super.c:get_super",
        "fs/super.c:iterate_supers_type",
        "fs/super.c:iterate_supers_type",
        "fs/super.c:iterate_supers",
        "fs/super.c:iterate_supers",
        "fs/super.c:__iterate_supers",
        "fs/super.c:__iterate_supers",
        "fs/super.c:sget",
        "fs/super.c:sget_fc",
        "fs/super.c:generic_shutdown_super",
        "fs/super.c:put_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493341960,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/char_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_purge",
        "fs/char_dev.c:cd_forget",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493345252,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:inode_get_bytes",
        "fs/stat.c:inode_sub_bytes",
        "fs/stat.c:inode_add_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493352164,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:finalize_exec",
        "fs/exec.c:__set_task_comm",
        "fs/exec.c:__get_task_comm",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/exec.c:unregister_binfmt",
        "fs/exec.c:__register_binfmt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493370932,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:fifo_open",
        "fs/pipe.c:fifo_open",
        "fs/pipe.c:put_pipe_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493412216,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:vfs_readlink",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:vfs_link",
        "fs/namei.c:vfs_unlink",
        "fs/namei.c:vfs_tmpfile",
        "fs/namei.c:lookup_open",
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_init",
        "fs/namei.c:__lookup_slow",
        "fs/namei.c:follow_up",
        "fs/namei.c:set_root",
        "fs/namei.c:inode_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493421040,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_modown",
        "fs/fcntl.c:setfl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493426924,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493461616,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_tmpfile",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_exchange",
        "fs/dcache.c:d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:d_rehash",
        "fs/dcache.c:__d_lookup",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_instantiate_new",
        "fs/dcache.c:__d_instantiate",
        "fs/dcache.c:d_set_fallthru",
        "fs/dcache.c:d_alloc",
        "fs/dcache.c:shrink_dcache_parent",
        "fs/dcache.c:d_set_mounted",
        "fs/dcache.c:d_set_mounted",
        "fs/dcache.c:d_set_mounted",
        "fs/dcache.c:path_has_submounts",
        "fs/dcache.c:d_walk",
        "fs/dcache.c:d_walk",
        "fs/dcache.c:d_walk",
        "fs/dcache.c:d_walk",
        "fs/dcache.c:dentry_lru_isolate_shrink",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:d_prune_aliases",
        "fs/dcache.c:d_find_any_alias",
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput",
        "fs/dcache.c:__lock_parent",
        "fs/dcache.c:__lock_parent",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop",
        "fs/dcache.c:take_dentry_name_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493487392,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__wait_on_freeing_inode",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:discard_new_inode",
        "fs/inode.c:unlock_new_inode",
        "fs/inode.c:new_inode_pseudo",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:invalidate_inodes",
        "fs/inode.c:invalidate_inodes",
        "fs/inode.c:evict_inodes",
        "fs/inode.c:evict_inodes",
        "fs/inode.c:evict",
        "fs/inode.c:evict",
        "fs/inode.c:clear_inode",
        "fs/inode.c:__remove_inode_hash",
        "fs/inode.c:__remove_inode_hash",
        "fs/inode.c:__insert_inode_hash",
        "fs/inode.c:__insert_inode_hash",
        "fs/inode.c:inode_sb_list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493504484,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:set_close_on_exec",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/file.c:put_unused_fd",
        "fs/file.c:__alloc_fd",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/file.c:get_files_struct",
        "fs/file.c:dup_fd",
        "fs/file.c:dup_fd",
        "fs/file.c:expand_files",
        "fs/file.c:expand_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493510388,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:unregister_filesystem",
        "fs/filesystems.c:register_filesystem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493518252,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mntns_get",
        "fs/namespace.c:current_chrooted",
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:path_is_under",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/namespace.c:unlock_mount",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:attach_recursive_mnt",
        "fs/namespace.c:drop_collected_mounts",
        "fs/namespace.c:dissolve_on_fput",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:ksys_umount",
        "fs/namespace.c:__detach_mounts",
        "fs/namespace.c:may_umount",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/namespace.c:get_mountpoint",
        "fs/namespace.c:sb_prepare_remount_readonly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493562208,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:simple_xattr_list_add",
        "fs/xattr.c:simple_xattr_list",
        "fs/xattr.c:simple_xattr_set",
        "fs/xattr.c:simple_xattr_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493570132,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:empty_dir_readdir",
        "fs/libfs.c:simple_release_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/libfs.c:simple_pin_fs",
        "fs/libfs.c:simple_empty",
        "fs/libfs.c:simple_empty",
        "fs/libfs.c:dcache_readdir",
        "fs/libfs.c:dcache_readdir",
        "fs/libfs.c:dcache_dir_lseek",
        "fs/libfs.c:scan_positives",
        "fs/libfs.c:scan_positives",
        "fs/libfs.c:scan_positives"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493606584,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:wb_writeback",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:inode_wait_for_writeback",
        "fs/fs-writeback.c:__inode_wait_for_writeback",
        "fs/fs-writeback.c:sb_clear_inode_writeback",
        "fs/fs-writeback.c:sb_mark_inode_writeback",
        "fs/fs-writeback.c:inode_io_list_del",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493614420,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/pnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_mnt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493636816,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__dentry_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493640860,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:unshare_fs_struct",
        "fs/fs_struct.c:unshare_fs_struct",
        "fs/fs_struct.c:copy_fs_struct",
        "fs/fs_struct.c:exit_fs",
        "fs/fs_struct.c:exit_fs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:chroot_fs_refs",
        "fs/fs_struct.c:set_fs_pwd",
        "fs/fs_struct.c:set_fs_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493646160,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fs_pin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_pin.c:pin_kill",
        "fs/fs_pin.c:pin_kill",
        "fs/fs_pin.c:pin_insert",
        "fs/fs_pin.c:pin_remove",
        "fs/fs_pin.c:pin_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493664240,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:try_to_free_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "fs/buffer.c:__bforget",
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:__set_page_dirty",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers",
        "fs/buffer.c:sync_mapping_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493706456,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/block_dev.c:blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:bd_abort_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:bd_acquire",
        "fs/block_dev.c:nr_blockdev_pages",
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493716692,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_bio_end_io",
        "fs/direct-io.c:dio_bio_end_aio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493726176,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common",
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493728920,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/notify/fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/notify/fsnotify.c:fsnotify_sb_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493730892,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_flush_notify",
        "fs/notify/notification.c:fsnotify_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493731944,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_destroy_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493733300,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/mark.c:fsnotify_grab_connector",
        "fs/notify/mark.c:fsnotify_free_mark",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493741292,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/notify/dnotify/dnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/notify/dnotify/dnotify.c:dnotify_flush",
        "fs/notify/dnotify/dnotify.c:dnotify_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493745796,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_ioctl",
        "fs/notify/inotify/inotify_user.c:inotify_ioctl",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493751472,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493754160,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark",
        "fs/notify/fanotify/fanotify_user.c:fanotify_ioctl",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_release",
        "fs/notify/fanotify/fanotify_user.c:fanotify_write",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493769432,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_remove",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493776728,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493779280,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_show",
        "fs/timerfd.c:timerfd_read",
        "fs/timerfd.c:timerfd_poll",
        "fs/timerfd.c:timerfd_release",
        "fs/timerfd.c:timerfd_release",
        "fs/timerfd.c:timerfd_clock_was_set",
        "fs/timerfd.c:timerfd_triggered"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493784908,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_show_fdinfo",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_read",
        "fs/eventfd.c:eventfd_ctx_remove_wait_queue",
        "fs/eventfd.c:eventfd_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493789040,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_show_fdinfo",
        "fs/userfaultfd.c:__wake_userfault",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493810060,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__arm64_sys_io_cancel",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_cancel",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_complete",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_nr_sub",
        "fs/aio.c:free_ioctx_users",
        "fs/aio.c:kiocb_set_cancel_fn",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_ring_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493837180,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_submit_sqe",
        "fs/io_uring.c:io_queue_link_head",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:__io_submit_sqe",
        "fs/io_uring.c:io_req_defer",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_poll_wake",
        "fs/io_uring.c:io_poll_complete_work",
        "fs/io_uring.c:io_poll_remove_one",
        "fs/io_uring.c:io_send_recvmsg",
        "fs/io_uring.c:io_cqring_add_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493863316,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_layout_busy_page",
        "fs/dax.c:dax_lock_page",
        "fs/dax.c:dax_unlock_entry",
        "fs/dax.c:get_unlocked_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493869952,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493878128,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/crypto/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493882192,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:do_remove_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493887864,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:put_crypt_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493889424,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:find_or_insert_direct_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493916896,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_start",
        "fs/locks.c:show_fd_locks",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:lease_get_mtime",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:locks_mandatory_locked",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:posix_test_lock",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/locks.c:locks_delete_block",
        "fs/locks.c:locks_insert_global_locks",
        "fs/locks.c:locks_move_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493978120,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493992456,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493993748,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/drop_caches.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/drop_caches.c:drop_pagecache_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493995592,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:do_handle_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494020288,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqinfo",
        "fs/quota/dquot.c:dquot_set_dqinfo",
        "fs/quota/dquot.c:dquot_get_state",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:do_get_dqblk",
        "fs/quota/dquot.c:dquot_enable",
        "fs/quota/dquot.c:dquot_resume",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_drop",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dquot_add_space",
        "fs/quota/dquot.c:dquot_add_inodes",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqcache_shrink_scan",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dquot_commit",
        "fs/quota/dquot.c:unregister_quota_format",
        "fs/quota/dquot.c:register_quota_format"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494062536,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494069532,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_reg_release",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:proc_entry_rundown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494096548,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pident_readdir",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_fill_cache",
        "fs/proc/base.c:task_dump_owner",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_root_link",
        "fs/proc/base.c:proc_cwd_link",
        "fs/proc/base.c:proc_cwd_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494105864,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494107960,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494115368,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494125208,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/proc/namespaces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/namespaces.c:proc_ns_dir_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494132588,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:unregister_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:__register_sysctl_table",
        "fs/proc/proc_sysctl.c:sysctl_follow_link",
        "fs/proc/proc_sysctl.c:proc_sys_compare",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_evict_inode",
        "fs/proc/proc_sysctl.c:proc_sys_make_inode",
        "fs/proc/proc_sysctl.c:insert_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494141528,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/proc/proc_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_net.c:get_proc_task_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494164424,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/dir.c:pr_cont_kernfs_path",
        "fs/kernfs/dir.c:pr_cont_kernfs_name",
        "fs/kernfs/dir.c:kernfs_path_from_node",
        "fs/kernfs/dir.c:kernfs_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494174848,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "fs/kernfs/file.c:kernfs_fop_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494183128,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_remove_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494184476,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/sysfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/symlink.c:sysfs_delete_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494188232,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/sysfs/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494189704,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/configfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/inode.c:configfs_hash_and_remove",
        "fs/configfs/inode.c:configfs_drop_dentry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494198068,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/configfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_unregister_subsystem",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/configfs/dir.c:configfs_unregister_group",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_dir_lseek",
        "fs/configfs/dir.c:configfs_readdir",
        "fs/configfs/dir.c:configfs_readdir",
        "fs/configfs/dir.c:configfs_readdir",
        "fs/configfs/dir.c:configfs_dir_close",
        "fs/configfs/dir.c:configfs_dir_open",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_rmdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_do_depend_item",
        "fs/configfs/dir.c:configfs_new_dirent",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494208760,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/configfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:configfs_symlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494215872,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/dcookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:get_dcookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494221816,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494238240,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_rereserve_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494285536,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_clear_inode_es",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:__es_shrink",
        "fs/ext4/extents_status.c:ext4_es_remove_extent",
        "fs/ext4/extents_status.c:ext4_es_cache_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494300548,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494349132,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_da_update_reserve_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494413796,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_generate_from_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494449532,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/ext4/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494495468,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494580796,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_init_journal_params",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:ext4_journal_commit_callback",
        "fs/ext4/super.c:ext4_journal_commit_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494664768,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_file_inode",
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_unlock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2_journal_lock_updates",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494670044,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494685248,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494687748,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494699540,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_ack_err",
        "fs/jbd2/journal.c:jbd2_journal_clear_err",
        "fs/jbd2/journal.c:__journal_abort_soft",
        "fs/jbd2/journal.c:__journal_abort_soft",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_start_commit",
        "fs/jbd2/journal.c:jbd2_log_start_commit",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494720240,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/squashfs/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_cache_put",
        "fs/squashfs/cache.c:squashfs_cache_get",
        "fs/squashfs/cache.c:squashfs_cache_get",
        "fs/squashfs/cache.c:squashfs_cache_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494754624,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlb_file_setup",
        "fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs",
        "fs/hugetlbfs/inode.c:hugetlbfs_statfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494756452,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fat/cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/cache.c:fat_get_cluster",
        "fs/fat/cache.c:fat_cache_inval_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494768700,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/dir.c:__fat_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494780552,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494795892,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_detach",
        "fs/fat/inode.c:fat_detach",
        "fs/fat/inode.c:fat_attach",
        "fs/fat/inode.c:fat_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494807624,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fat/nfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494809612,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_revalidate_shortname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494869736,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/exportfs/expfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494872380,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/nls/nls_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/nls/nls_base.c:find_nls",
        "fs/nls/nls_base.c:unregister_nls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494887208,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/dev.c:fuse_dev_poll",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:request_wait_answer",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:fuse_request_end",
        "fs/fuse/dev.c:flush_bg_queue",
        "fs/fuse/dev.c:fuse_queue_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494912952,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_release_nowrite",
        "fs/fuse/dir.c:fuse_set_nowrite",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_settime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494941632,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_notify_poll_wakeup",
        "fs/fuse/file.c:fuse_file_poll",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_send_writepage",
        "fs/fuse/file.c:fuse_write_update_size",
        "fs/fuse/file.c:fuse_async_req_send",
        "fs/fuse/file.c:fuse_aio_complete",
        "fs/fuse/file.c:fuse_aio_complete",
        "fs/fuse/file.c:fuse_range_is_writeback",
        "fs/fuse/file.c:fuse_prepare_release",
        "fs/fuse/file.c:fuse_prepare_release",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/file.c:fuse_link_write_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494949552,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_dev_free",
        "fs/fuse/inode.c:fuse_dev_install",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:fuse_iget",
        "fs/fuse/inode.c:fuse_change_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494954788,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_max_background_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494961336,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494966296,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/debugfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494979928,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/tracefs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/tracefs/inode.c:tracefs_remove_recursive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494982232,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/pstore/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/pstore/inode.c:pstore_mkfile",
        "fs/pstore/inode.c:pstore_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494984536,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "fs/pstore/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494996668,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495003976,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:msgctl_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495028312,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/sem.c:freeary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495040164,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:shmctl_down",
        "ipc/shm.c:exit_shm",
        "ipc/shm.c:shm_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495048884,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_getsetattr",
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:mqueue_poll_file",
        "ipc/mqueue.c:mqueue_flush_file",
        "ipc/mqueue.c:mqueue_read_file",
        "ipc/mqueue.c:mqueue_create_attr",
        "ipc/mqueue.c:mqueue_create_attr",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_get_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495057420,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "ipc/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/namespace.c:ipcns_get",
        "ipc/namespace.c:free_ipcs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495060052,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector",
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495066868,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_lookup",
        "security/keys/key.c:key_payload_reserve",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_user_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495071936,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_destroy",
        "security/keys/keyring.c:keyring_instantiate",
        "security/keys/keyring.c:key_free_user_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495086296,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495102076,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_key_users_start",
        "security/keys/proc.c:proc_keys_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495165184,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_compute_av",
        "security/selinux/avc.c:avc_compute_av",
        "security/selinux/avc.c:avc_ss_reset",
        "security/selinux/avc.c:avc_flush",
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495195880,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_invalidate_secctx",
        "security/selinux/hooks.c:selinux_task_to_inode",
        "security/selinux/hooks.c:selinux_inode_setsecurity",
        "security/selinux/hooks.c:selinux_inode_post_setxattr",
        "security/selinux/hooks.c:selinux_inode_free_security",
        "security/selinux/hooks.c:selinux_bprm_committed_creds",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "security/selinux/hooks.c:sb_finish_set_opts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495234636,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/selinux/netif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/netif.c:sel_netif_netdev_notifier_handler",
        "security/selinux/netif.c:sel_netif_flush",
        "security/selinux/netif.c:sel_netif_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495236792,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/selinux/netnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/netnode.c:sel_netnode_flush",
        "security/selinux/netnode.c:sel_netnode_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495237832,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/selinux/netport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/netport.c:sel_netport_flush",
        "security/selinux/netport.c:sel_netport_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495238840,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/selinux/ibpkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ibpkey.c:sel_ib_pkey_flush",
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495248072,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495296532,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495330368,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_netlabel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495368348,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/tomoyo/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/audit.c:tomoyo_read_log",
        "security/tomoyo/audit.c:tomoyo_write_log2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495388504,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_answer",
        "security/tomoyo/common.c:tomoyo_write_answer",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "security/tomoyo/common.c:tomoyo_write_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495412912,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/tomoyo/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495452528,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:multi_transaction_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495469576,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/apparmor/path.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495525548,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/apparmor/secid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/secid.c:aa_alloc_secid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495531064,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:update_file_ctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495534292,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/apparmor/policy_ns.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495541084,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495568816,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495573604,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/yama/yama_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/yama/yama_lsm.c:yama_ptracer_add",
        "security/yama/yama_lsm.c:yama_relation_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495581368,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_inode_free",
        "security/integrity/iint.c:integrity_inode_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495608072,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495681876,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "crypto/scompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495742296,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "crypto/jitterentropy-kcapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/jitterentropy-kcapi.c:jent_kcapi_random",
        "crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495781796,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:punt_bios_to_rescuer",
        "block/bio.c:bio_alloc_rescue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495788768,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/elevator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/elevator.c:elv_iosched_show",
        "block/elevator.c:elevator_init_mq",
        "block/elevator.c:elv_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495819092,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_max_sectors_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495821584,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495828916,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-ioc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:get_task_io_context",
        "block/blk-ioc.c:create_task_io_context",
        "block/blk-ioc.c:ioc_clear_queue",
        "block/blk-ioc.c:ioc_clear_queue",
        "block/blk-ioc.c:exit_io_context",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-ioc.c:ioc_release_fn",
        "block/blk-ioc.c:ioc_release_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495865524,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq.c:dispatch_rq_from_ctx",
        "block/blk-mq.c:flush_busy_ctx",
        "block/blk-mq.c:blk_mq_requeue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495877992,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-stat.c:blk_stat_add_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495886348,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495900908,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_check_events",
        "block/genhd.c:disk_clear_events",
        "block/genhd.c:disk_clear_events",
        "block/genhd.c:disk_flush_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:disk_block_events",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495914332,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495918716,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/badblocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/badblocks.c:badblocks_clear",
        "block/badblocks.c:badblocks_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495965468,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495982356,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkcg_punt_bio_submit",
        "block/blk-cgroup.c:blkcg_can_attach",
        "block/blk-cgroup.c:blkcg_init_queue",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "block/blk-cgroup.c:blkcg_destroy_blkgs",
        "block/blk-cgroup.c:blkcg_print_stat",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_print_blkgs",
        "block/blk-cgroup.c:blkcg_reset_stats",
        "block/blk-cgroup.c:blkg_destroy_all",
        "block/blk-cgroup.c:blkg_destroy_all",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_async_bio_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496001008,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496013816,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-iocost.c:ioc_rqos_queue_depth_changed",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496027364,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/mq-deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/mq-deadline.c:dd_finish_request",
        "block/mq-deadline.c:dd_insert_requests",
        "block/mq-deadline.c:dd_bio_merge",
        "block/mq-deadline.c:dd_dispatch_request",
        "block/mq-deadline.c:deadline_next_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496069168,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-mq-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496089460,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "block/blk-pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-pm.c:blk_pre_runtime_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496091392,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/lockref.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496096256,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_reseed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496141816,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496146108,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_walk_stop",
        "lib/rhashtable.c:rhashtable_walk_start_check",
        "lib/rhashtable.c:rhashtable_walk_exit",
        "lib/rhashtable.c:rhashtable_walk_enter",
        "lib/rhashtable.c:rhashtable_rehash_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496150044,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/once.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/once.c:__do_once_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496151008,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496203988,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_add_owner"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496309960,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/textsearch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/textsearch.c:textsearch_unregister",
        "lib/textsearch.c:textsearch_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496310816,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_cpu_dead",
        "lib/percpu_counter.c:percpu_counter_cpu_dead",
        "lib/percpu_counter.c:__percpu_counter_init",
        "lib/percpu_counter.c:__percpu_counter_sum",
        "lib/percpu_counter.c:percpu_counter_add_batch",
        "lib/percpu_counter.c:percpu_counter_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496356404,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496359192,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-al-fic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496361648,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-dw-apb-ictl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496362760,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-sunxi-nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496369448,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-gic-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-common.c:gic_configure_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496370900,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-gic-v2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496401128,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_restore_enable",
        "drivers/irqchip/irq-gic-v3-its.c:its_save_disable",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_msi_prepare",
        "drivers/irqchip/irq-gic-v3-its.c:its_create_device",
        "drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand",
        "drivers/irqchip/irq-gic-v3-its.c:its_send_single_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496410124,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_mask",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_unmask",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496411948,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-brcmstb-l2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume",
        "drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend",
        "drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle",
        "drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_mask_and_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496414008,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-mtk-sysirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496417100,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-imx-gpcv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_mask",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_unmask",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_set_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496418400,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-mvebu-gicp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_free",
        "drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc",
        "drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496421320,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-mvebu-odmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_free",
        "drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc",
        "drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496426528,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-mvebu-sei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_unmask_irq",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_mask_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496429264,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-ls-scfg-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_free",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496433432,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-meson-gpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496435832,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/qcom-pdc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496438188,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/irqchip/irq-imx-irqsteer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496445576,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/bus/hisi_lpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/hisi_lpc.c:hisi_lpc_target_out",
        "drivers/bus/hisi_lpc.c:hisi_lpc_target_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496452408,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/bus/fsl-mc/mc-sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/fsl-mc/mc-sys.c:mc_send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496529008,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/pinctrl-amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496558648,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/pinctrl-rockchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set",
        "drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496569120,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/pinctrl-single.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handle",
        "drivers/pinctrl/pinctrl-single.c:pcs_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496586232,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask",
        "drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496594676,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/bcm/pinctrl-bcm2835.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_disable",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496603400,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_set",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_input",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_unmask",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496608264,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/bcm/pinctrl-ns2-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_get_pull",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_set_pull",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496628496,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_type",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_wake",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_unmask",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_mask",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496635196,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496649196,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/sh-pfc/pinctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_disable_free",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_request_enable",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496666272,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pinctrl/sunxi/pinctrl-sunxi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_unmask",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_mask",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_set_type",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_set",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_set",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496709492,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_next",
        "drivers/gpio/gpiolib.c:gpiolib_seq_start",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_find",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496748628,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:gpiod_export"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496763504,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_in",
        "drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg",
        "drivers/gpio/gpio-mmio.c:bgpio_set_set",
        "drivers/gpio/gpio-mmio.c:bgpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496768184,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/gpio/gpio-davinci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-davinci.c:davinci_direction_out",
        "drivers/gpio/gpio-davinci.c:davinci_direction_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496773564,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/gpio/gpio-mpc8xxx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type",
        "drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type",
        "drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_set_type",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_set_type",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_mask",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_unmask",
        "drivers/gpio/gpio-mpc8xxx.c:ls1028a_gpio_dir_in_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496780364,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/gpio/gpio-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply",
        "drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state",
        "drivers/gpio/gpio-mvebu.c:mvebu_pwm_free",
        "drivers/gpio/gpio-mvebu.c:mvebu_pwm_request",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_unmask",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_mask",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_unmask",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_mask",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496788280,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/gpio/gpio-pl061.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-pl061.c:pl061_irq_ack",
        "drivers/gpio/gpio-pl061.c:pl061_irq_unmask",
        "drivers/gpio/gpio-pl061.c:pl061_irq_mask",
        "drivers/gpio/gpio-pl061.c:pl061_irq_type",
        "drivers/gpio/gpio-pl061.c:pl061_direction_output",
        "drivers/gpio/gpio-pl061.c:pl061_direction_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496802132,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/gpio/gpio-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in",
        "drivers/gpio/gpio-xgene.c:xgene_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496804768,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/gpio/gpio-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-xilinx.c:xgpio_dir_out",
        "drivers/gpio/gpio-xilinx.c:xgpio_dir_in",
        "drivers/gpio/gpio-xilinx.c:xgpio_set_multiple",
        "drivers/gpio/gpio-xilinx.c:xgpio_set_multiple",
        "drivers/gpio/gpio-xilinx.c:xgpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496822536,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_cfg_access_unlock",
        "drivers/pci/access.c:pci_cfg_access_trylock",
        "drivers/pci/access.c:pci_cfg_access_lock",
        "drivers/pci/access.c:pci_user_write_config_dword",
        "drivers/pci/access.c:pci_user_write_config_word",
        "drivers/pci/access.c:pci_user_write_config_byte",
        "drivers/pci/access.c:pci_user_read_config_dword",
        "drivers/pci/access.c:pci_user_read_config_word",
        "drivers/pci/access.c:pci_user_read_config_byte",
        "drivers/pci/access.c:pci_wait_cfg",
        "drivers/pci/access.c:pci_bus_set_ops",
        "drivers/pci/access.c:pci_bus_write_config_dword",
        "drivers/pci/access.c:pci_bus_write_config_word",
        "drivers/pci/access.c:pci_bus_write_config_byte",
        "drivers/pci/access.c:pci_bus_read_config_dword",
        "drivers/pci/access.c:pci_bus_read_config_word",
        "drivers/pci/access.c:pci_bus_read_config_byte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496862648,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:resource_alignment_store",
        "drivers/pci/pci.c:resource_alignment_show",
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment",
        "drivers/pci/pci.c:pci_dev_complete_resume",
        "drivers/pci/pci.c:pci_dev_adjust_pme"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496889704,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_unregister_driver",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:remove_id_store",
        "drivers/pci/pci-driver.c:pci_add_dynid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496990252,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496996372,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497083664,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497120520,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pci/controller/pcie-xilinx-nwl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_unmask_leg_irq",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_mask_leg_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497152096,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pci/controller/pcie-mobiveil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_unmask_intx_irq",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_mask_intx_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497162592,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497179228,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pci/controller/dwc/pci-keystone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_unmask",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497223420,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_route_clr_table",
        "drivers/rapidio/rio.c:rio_route_get_entry",
        "drivers/rapidio/rio.c:rio_route_add_entry",
        "drivers/rapidio/rio.c:rio_get_asm",
        "drivers/rapidio/rio.c:rio_get_comptag",
        "drivers/rapidio/rio.c:rio_map_outb_region",
        "drivers/rapidio/rio.c:rio_map_inb_region",
        "drivers/rapidio/rio.c:rio_release_inb_pwrite",
        "drivers/rapidio/rio.c:rio_request_inb_pwrite",
        "drivers/rapidio/rio.c:rio_del_device",
        "drivers/rapidio/rio.c:rio_free_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497367508,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/video/fbdev/mx3fb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:sdc_init_panel",
        "drivers/video/fbdev/mx3fb.c:sdc_disable_channel",
        "drivers/video/fbdev/mx3fb.c:sdc_enable_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497382252,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_acquire_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497433176,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enter_noirq",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_stopped",
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/acpi/ec.c:ec_transaction_completed",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497683948,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/acpi/apei/erst.c:erst_get_record_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497694300,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/acpi/apei/ghes.c:ghes_sdei_critical_callback",
        "drivers/acpi/apei/ghes.c:ghes_sdei_normal_callback",
        "drivers/acpi/apei/ghes.c:ghes_notify_sea",
        "drivers/acpi/apei/ghes.c:ghes_notify_hed",
        "drivers/acpi/apei/ghes.c:ghes_irq_func",
        "drivers/acpi/apei/ghes.c:ghes_poll_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497702168,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/acpi/arm64/iort.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/arm64/iort.c:iort_iommu_msi_get_resv_regions",
        "drivers/acpi/arm64/iort.c:iort_iommu_msi_get_resv_regions",
        "drivers/acpi/arm64/iort.c:iort_find_domain_token",
        "drivers/acpi/arm64/iort.c:iort_deregister_domain_token",
        "drivers/acpi/arm64/iort.c:iort_register_domain_token"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497756660,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/clk/clk.c:clk_enable_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497776408,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497780516,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/clk-gate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-gate.c:clk_gate_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497781480,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/clk-multiplier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497783520,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/clk-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-mux.c:clk_mux_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497787160,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/clk-fractional-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497796332,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/clk-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-xgene.c:xgene_clk_set_rate",
        "drivers/clk/clk-xgene.c:xgene_clk_disable",
        "drivers/clk/clk-xgene.c:xgene_clk_enable",
        "drivers/clk/clk-xgene.c:xgene_clk_pmd_set_rate",
        "drivers/clk/clk-xgene.c:xgene_clk_pmd_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497815708,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/bcm/clk-bcm2835.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_set_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_off",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497821156,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/berlin/berlin2-div.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_disable",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_enable",
        "drivers/clk/berlin/berlin2-div.c:berlin2_div_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497824256,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/hisilicon/clkgate-separated.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable",
        "drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497825264,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/hisilicon/clkdivider-hi6220.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497826380,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/hisilicon/clk-hisi-phase.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497828856,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/hisilicon/reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/reset.c:hisi_reset_deassert",
        "drivers/clk/hisilicon/reset.c:hisi_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497833100,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/imx/clk-composite-8m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497835552,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/imx/clk-divider-gate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_disable",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate",
        "drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497836988,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/imx/clk-fixup-div.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497837672,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/imx/clk-fixup-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497840000,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/imx/clk-gate2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused",
        "drivers/clk/imx/clk-gate2.c:clk_gate2_disable",
        "drivers/clk/imx/clk-gate2.c:clk_gate2_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497842520,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/imx/clk-pfdv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable",
        "drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497854160,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/imx/clk-lpcg-scu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_disable",
        "drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497903184,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/mediatek/clk-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock",
        "drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497917176,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/meson/clk-mpll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/meson/clk-mpll.c:mpll_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497932968,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/renesas/r9a06g032-clocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497934380,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/renesas/rcar-gen3-cpg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/rcar-gen3-cpg.c:cpg_reg_modify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497938996,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/renesas/renesas-cpg-mssr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497948372,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/rockchip/clk-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb",
        "drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497950500,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/rockchip/clk-half-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497951576,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/rockchip/clk-inverter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497954244,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/rockchip/clk-ddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497954944,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/rockchip/softrst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert",
        "drivers/clk/rockchip/softrst.c:rockchip_softrst_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497960044,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi/clk-factors.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-factors.c:clk_factors_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497963824,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi/clk-a10-ve.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_deassert",
        "drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497964696,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi/clk-mod0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-mod0.c:mmc_set_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497965408,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi/clk-sun4i-display.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_deassert",
        "drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497966172,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_rate",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_parent",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_enable",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497968980,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi/clk-sun9i-mmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497969936,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi/clk-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert",
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497971720,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi/clk-sun9i-cpus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_clk_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497974204,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_mmc_timing.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_set_mmc_timing_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497974940,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_deassert",
        "drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_assert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497975840,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_div.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497977368,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_frac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_set_rate",
        "drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_disable",
        "drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497978064,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_gate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497980508,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497981724,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_mult.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497982424,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_phase.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_set_phase"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497983636,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_sdm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable",
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable",
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable",
        "drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497985488,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_nk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497987236,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_nkm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497989260,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_nkmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497991168,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_nm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate",
        "drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497993256,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/sunxi-ng/ccu_mp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497995848,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clk/versatile/clk-sp810.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498008000,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_run_dependencies"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498013916,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma/virt-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/virt-dma.c:vchan_complete",
        "drivers/dma/virt-dma.c:vchan_tx_desc_free",
        "drivers/dma/virt-dma.c:vchan_tx_submit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498022000,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma/amba-pl08x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/amba-pl08x.c:pl08x_debugfs_show",
        "drivers/dma/amba-pl08x.c:pl08x_irq",
        "drivers/dma/amba-pl08x.c:pl08x_resume",
        "drivers/dma/amba-pl08x.c:pl08x_pause",
        "drivers/dma/amba-pl08x.c:pl08x_synchronize",
        "drivers/dma/amba-pl08x.c:pl08x_terminate_all",
        "drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic",
        "drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg",
        "drivers/dma/amba-pl08x.c:pl08x_prep_dma_memcpy",
        "drivers/dma/amba-pl08x.c:pl08x_issue_pending",
        "drivers/dma/amba-pl08x.c:pl08x_issue_pending",
        "drivers/dma/amba-pl08x.c:pl08x_free_chan_resources",
        "drivers/dma/amba-pl08x.c:pl08x_phy_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498039704,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma/bcm2835-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_synchronize",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_cyclic",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_slave_sg",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_memcpy",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_issue_pending",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498048216,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_xor_status",
        "drivers/dma/mv_xor.c:mv_xor_free_chan_resources",
        "drivers/dma/mv_xor.c:mv_xor_prep_dma_xor",
        "drivers/dma/mv_xor.c:mv_xor_alloc_chan_resources",
        "drivers/dma/mv_xor.c:mv_xor_tx_submit",
        "drivers/dma/mv_xor.c:mv_xor_tasklet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498054516,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma/mv_xor_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_issue_pending",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_tx_submit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498062276,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma/ipu/ipu_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_handler",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_handler",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_unmap",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_map",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_status",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_ack",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_mask",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498073896,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all",
        "drivers/dma/ipu/ipu_idmac.c:idmac_pause",
        "drivers/dma/ipu/ipu_idmac.c:idmac_issue_pending",
        "drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg",
        "drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498089760,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/soc/fsl/qbman/bman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498091260,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/soc/fsl/qbman/qman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498094984,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/soc/fsl/qbman/bman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman.c:bman_create_affine_portal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498103468,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_delete_cgr",
        "drivers/soc/fsl/qbman/qman.c:qman_create_cgr",
        "drivers/soc/fsl/qbman/qman.c:qm_congestion_task",
        "drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal",
        "drivers/soc/fsl/qbman/qman.c:qman_create_affine_portal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498137056,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/soc/qcom/rpmh-rsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data",
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data",
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data",
        "drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done",
        "drivers/soc/qcom/rpmh-rsc.c:tcs_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498138976,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/soc/qcom/rpmh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/rpmh.c:rpmh_invalidate",
        "drivers/soc/qcom/rpmh.c:rpmh_flush",
        "drivers/soc/qcom/rpmh.c:rpmh_write_batch",
        "drivers/soc/qcom/rpmh.c:__rpmh_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498143772,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/soc/renesas/rcar-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498150584,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/soc/sunxi/sunxi_sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_release",
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_claim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498157296,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/virtio/virtio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove",
        "drivers/virtio/virtio.c:virtio_config_enable",
        "drivers/virtio/virtio.c:virtio_config_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498176148,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:vm_del_vqs",
        "drivers/virtio/virtio_mmio.c:vm_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498185920,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_setup_vq",
        "drivers/virtio/virtio_pci_common.c:vp_vring_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498194684,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:return_free_pages_to_mm",
        "drivers/virtio/virtio_balloon.c:stats_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498205888,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_cancel_free_callback",
        "drivers/xen/grant-table.c:gnttab_request_free_callback",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/xen/grant-table.c:gnttab_handle_deferred",
        "drivers/xen/grant-table.c:put_free_entry",
        "drivers/xen/grant-table.c:get_free_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498229588,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:xen_debug_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498238976,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498243004,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xs_suspend",
        "drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch",
        "drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch",
        "drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch",
        "drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch",
        "drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg",
        "drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg",
        "drivers/xen/xenbus/xenbus_xs.c:xs_request_exit",
        "drivers/xen/xenbus/xenbus_xs.c:xs_suspend_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498338272,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/reset/reset-meson.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/reset-meson.c:meson_reset_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498339384,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/reset/reset-simple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/reset-simple.c:reset_simple_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498357564,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:redirected_tty_write",
        "drivers/tty/tty_io.c:start_tty",
        "drivers/tty/tty_io.c:stop_tty",
        "drivers/tty/tty_io.c:check_tty_count",
        "drivers/tty/tty_io.c:tty_add_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498375636,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498395496,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498397016,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:get_ldops",
        "drivers/tty/tty_ldisc.c:tty_unregister_ldisc",
        "drivers/tty/tty_ldisc.c:tty_register_ldisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498409108,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_open",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_port.c:tty_port_block_til_ready",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_tty_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503946548,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498416696,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_get_pgrp",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:get_current_tty",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498424200,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_set_termios",
        "drivers/tty/pty.c:pty_flush_buffer",
        "drivers/tty/pty.c:pty_set_pktmode",
        "drivers/tty/pty.c:pty_write",
        "drivers/tty/pty.c:pty_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498430764,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498440408,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:__vt_event_dequeue",
        "drivers/tty/vt/vt_ioctl.c:__vt_event_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498444740,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/vt/vc_screen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498475156,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_clr_kbd_mode_bit",
        "drivers/tty/vt/keyboard.c:vt_set_kbd_mode_bit",
        "drivers/tty/vt/keyboard.c:vt_reset_keyboard",
        "drivers/tty/vt/keyboard.c:vt_reset_keyboard",
        "drivers/tty/vt/keyboard.c:vt_reset_unicode",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdskbmeta",
        "drivers/tty/vt/keyboard.c:vt_do_kdskbmode",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/tty/vt/keyboard.c:kbd_bh",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_stop",
        "drivers/tty/vt/keyboard.c:vt_kbd_con_start",
        "drivers/tty/vt/keyboard.c:vt_get_leds",
        "drivers/tty/vt/keyboard.c:setledstate",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/keyboard.c:compute_shiftstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498496480,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vt_console_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498520628,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/hvc/hvc_console.c:hvc_write",
        "drivers/tty/hvc/hvc_console.c:hvc_hangup",
        "drivers/tty/hvc/hvc_console.c:hvc_open",
        "drivers/tty/hvc/hvc_console.c:hvc_port_destruct",
        "drivers/tty/hvc/hvc_console.c:hvc_get_by_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498528504,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_probe",
        "drivers/tty/hvc/hvc_xen.c:xencons_remove",
        "drivers/tty/hvc/hvc_xen.c:xen_pv_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498554392,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_hangup",
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_tiocmget",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_change_speed",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_update_mctrl",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498563772,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/8250/8250_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port",
        "drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work",
        "drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq",
        "drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout",
        "drivers/tty/serial/8250/8250_core.c:serial_do_unlink",
        "drivers/tty/serial/8250/8250_core.c:serial8250_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498590188,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498593940,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498609416,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498612352,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/8250/8250_fsl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498614572,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/8250/8250_dw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dw.c:dw8250_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498620128,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498638708,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:sbsa_uart_set_termios",
        "drivers/tty/serial/amba-pl011.c:pl011_set_termios",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts",
        "drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts",
        "drivers/tty/serial/amba-pl011.c:pl011_break_ctl",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498655596,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_resume_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_timeout",
        "drivers/tty/serial/imx.c:imx_uart_break_ctl",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_rxint",
        "drivers/tty/serial/imx.c:imx_uart_txint",
        "drivers/tty/serial/imx.c:imx_uart_rtsint",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498670604,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/meson_uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/meson_uart.c:meson_serial_port_write",
        "drivers/tty/serial/meson_uart.c:meson_serial_port_write",
        "drivers/tty/serial/meson_uart.c:meson_uart_set_termios",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_interrupt",
        "drivers/tty/serial/meson_uart.c:meson_uart_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498678412,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_console_write",
        "drivers/tty/serial/sccnxp.c:sccnxp_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_startup",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_termios",
        "drivers/tty/serial/sccnxp.c:sccnxp_break_ctl",
        "drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl",
        "drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl",
        "drivers/tty/serial/sccnxp.c:sccnxp_tx_empty",
        "drivers/tty/serial/sccnxp.c:sccnxp_stop_rx",
        "drivers/tty/serial/sccnxp.c:sccnxp_start_tx",
        "drivers/tty/serial/sccnxp.c:sccnxp_ist",
        "drivers/tty/serial/sccnxp.c:sccnxp_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498688568,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/msm_serial.c:__msm_console_write",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_set_termios",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_uart_irq",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_rx_dma",
        "drivers/tty/serial/msm_serial.c:msm_complete_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498699916,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/mvebu-uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498704100,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/owl-uart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/owl-uart.c:owl_uart_port_write",
        "drivers/tty/serial/owl-uart.c:owl_uart_port_write",
        "drivers/tty/serial/owl-uart.c:owl_uart_set_termios",
        "drivers/tty/serial/owl-uart.c:owl_uart_shutdown",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_irq",
        "drivers/tty/serial/owl-uart.c:owl_uart_tx_empty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498708052,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498726900,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:invalidate_batched_entropy",
        "drivers/char/random.c:invalidate_batched_entropy",
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:del_random_ready_callback",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:_crng_backtrack_protect",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_fast_load",
        "drivers/char/random.c:mix_pool_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498748968,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/char/ttyprintk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/ttyprintk.c:tpk_write",
        "drivers/char/ttyprintk.c:tpk_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498763672,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:port_has_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs",
        "drivers/char/virtio_console.c:find_port_by_vq",
        "drivers/char/virtio_console.c:find_port_by_id",
        "drivers/char/virtio_console.c:find_port_by_vtermno"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498837168,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_ops_from_fwnode",
        "drivers/iommu/iommu.c:iommu_device_unregister",
        "drivers/iommu/iommu.c:iommu_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498865136,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:free_cpu_cached_iovas",
        "drivers/iommu/iova.c:iova_rcache_get",
        "drivers/iommu/iova.c:iova_rcache_get",
        "drivers/iommu/iova.c:iova_rcache_insert",
        "drivers/iommu/iova.c:iova_rcache_insert",
        "drivers/iommu/iova.c:split_and_remove_iova",
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/iova.c:reserve_iova",
        "drivers/iommu/iova.c:queue_iova",
        "drivers/iommu/iova.c:fq_flush_timeout",
        "drivers/iommu/iova.c:__free_iova",
        "drivers/iommu/iova.c:find_iova",
        "drivers/iommu/iova.c:alloc_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498878624,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/iommu/arm-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard",
        "drivers/iommu/arm-smmu.c:arm_smmu_tlb_sync_context",
        "drivers/iommu/arm-smmu.c:arm_smmu_tlb_sync_global"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498897528,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/iommu/arm-smmu-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498911328,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/iommu/rockchip-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_unmap",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_iova_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498917956,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/iommu/qcom_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/qcom_iommu.c:qcom_iommu_iova_to_phys",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_unmap",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498920868,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_iotlb_sync",
        "drivers/iommu/virtio-iommu.c:viommu_iova_to_phys",
        "drivers/iommu/virtio-iommu.c:viommu_unmap",
        "drivers/iommu/virtio-iommu.c:viommu_map",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/iommu/virtio-iommu.c:viommu_del_mappings",
        "drivers/iommu/virtio-iommu.c:viommu_send_req_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498927288,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/connector/cn_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/connector/cn_queue.c:cn_queue_free_dev",
        "drivers/connector/cn_queue.c:cn_queue_del_callback",
        "drivers/connector/cn_queue.c:cn_queue_add_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498928696,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/connector/connector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/connector/connector.c:cn_proc_show",
        "drivers/connector/connector.c:cn_netlink_send_mult"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498967248,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:devices_kset_move_last"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498975460,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/bus.c:bus_sort_breadthfirst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498984456,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:driver_detach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498996500,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499003924,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devres_release_group",
        "drivers/base/devres.c:devres_remove_group",
        "drivers/base/devres.c:devres_close_group",
        "drivers/base/devres.c:devres_open_group",
        "drivers/base/devres.c:devres_release_all",
        "drivers/base/devres.c:devres_remove",
        "drivers/base/devres.c:devres_get",
        "drivers/base/devres.c:devres_find",
        "drivers/base/devres.c:devres_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499008264,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/attribute_container.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/attribute_container.c:attribute_container_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499027436,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_find_by_name",
        "drivers/base/swnode.c:software_node_to_swnode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499032160,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/devtmpfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devtmpfs.c:devtmpfs_delete_node",
        "drivers/base/devtmpfs.c:devtmpfs_create_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499035424,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499041292,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/power/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/common.c:dev_pm_put_subsys_data",
        "drivers/base/power/common.c:dev_pm_get_subsys_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499046844,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/qos.c:dev_pm_qos_constraints_destroy",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/base/power/qos.c:dev_pm_qos_read_value",
        "drivers/base/power/qos.c:dev_pm_qos_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499061540,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_drop_link",
        "drivers/base/power/runtime.c:pm_runtime_new_link",
        "drivers/base/power/runtime.c:__pm_runtime_use_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_set_autosuspend_delay",
        "drivers/base/power/runtime.c:pm_runtime_irq_safe",
        "drivers/base/power/runtime.c:pm_runtime_no_callbacks",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_forbid",
        "drivers/base/power/runtime.c:pm_runtime_enable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:__pm_runtime_resume",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_idle",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:pm_runtime_work",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio",
        "drivers/base/power/runtime.c:pm_runtime_suspended_time",
        "drivers/base/power/runtime.c:pm_runtime_active_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499063628,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499081628,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_pm_check_callbacks",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_propagate_wakeup_to_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499084868,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show",
        "drivers/base/power/wakeup.c:pm_save_wakeup_count",
        "drivers/base/power/wakeup.c:pm_wakeup_pending",
        "drivers/base/power/wakeup.c:pm_wakeup_timer_fn",
        "drivers/base/power/wakeup.c:device_wakeup_disable",
        "drivers/base/power/wakeup.c:device_wakeup_enable",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/base/power/wakeup.c:wakeup_source_add",
        "drivers/base/power/wakeup.c:wakeup_source_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499110264,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_add_device",
        "drivers/base/power/domain.c:genpd_free_dev_data",
        "drivers/base/power/domain.c:genpd_dev_pm_qos_notifier",
        "drivers/base/power/domain.c:genpd_lock_interruptible_spin",
        "drivers/base/power/domain.c:genpd_lock_nested_spin",
        "drivers/base/power/domain.c:genpd_lock_spin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499113272,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain_governor.c:default_suspend_ok"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499115948,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_resume",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:pm_clk_destroy",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:__pm_clk_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499121188,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:assign_fw",
        "drivers/base/firmware_loader/main.c:free_fw_priv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499147136,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_async_is_done",
        "drivers/base/regmap/regmap.c:regmap_async_complete_cb",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:regmap_lock_spinlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499213876,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_attr_do_show_backing_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499238836,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:kick_pending_request_queues",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499258204,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499336508,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/mfd/ezx-pcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ezx-pcap.c:ezx_pcap_remove",
        "drivers/mfd/ezx-pcap.c:pcap_adc_async",
        "drivers/mfd/ezx-pcap.c:pcap_adc_irq",
        "drivers/mfd/ezx-pcap.c:pcap_adc_trigger",
        "drivers/mfd/ezx-pcap.c:pcap_set_ts_bits",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_set_bits",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_read",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499391224,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/syscon.c:device_node_get_regmap",
        "drivers/mfd/syscon.c:of_syscon_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499403480,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499423888,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_acquire_lane"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499461404,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_forget",
        "drivers/nvdimm/badrange.c:badrange_add",
        "drivers/nvdimm/badrange.c:badrange_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499474556,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:alloc_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499485928,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499492180,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_remove_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499509312,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:timeline_fence_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499511416,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/dma-buf/sync_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_info_debugfs_show",
        "drivers/dma-buf/sync_debug.c:sync_file_debug_remove",
        "drivers/dma-buf/sync_debug.c:sync_file_debug_add",
        "drivers/dma-buf/sync_debug.c:sync_timeline_debug_remove",
        "drivers/dma-buf/sync_debug.c:sync_timeline_debug_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499521212,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/scsi/scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:scsi_device_lookup",
        "drivers/scsi/scsi.c:scsi_device_lookup_by_target",
        "drivers/scsi/scsi.c:__scsi_iterate_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499525448,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/hosts.c:scsi_remove_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499547712,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_try_target_reset",
        "drivers/scsi/scsi_error.c:scsi_try_bus_reset",
        "drivers/scsi/scsi_error.c:scsi_try_host_reset",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_error.c:scsi_eh_scmd_add",
        "drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed",
        "drivers/scsi/scsi_error.c:scsi_schedule_eh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499556616,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:sdev_evt_send",
        "drivers/scsi/scsi_lib.c:scsi_evt_thread",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_add_cmd_to_list",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/scsi/scsi_lib.c:scsi_dec_host_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499580296,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/scsi/scsi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_scan.c:scsi_forget_host",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:do_scan_async",
        "drivers/scsi/scsi_scan.c:scsi_alloc_target",
        "drivers/scsi/scsi_scan.c:scsi_target_destroy",
        "drivers/scsi/scsi_scan.c:scsi_complete_async_scans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499592848,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:scsi_remove_target",
        "drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext",
        "drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499609656,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/scsi/scsi_dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_dh.c:__scsi_dh_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499645972,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_kref_release",
        "drivers/scsi/sr.c:sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499656632,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499693876,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_finalize_port_ops",
        "drivers/ata/libata-core.c:ata_dev_init",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-core.c:ata_exec_internal_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499751540,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach",
        "drivers/ata/libata-scsi.c:ata_scsi_queuecmd",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill",
        "drivers/ata/libata-scsi.c:__ata_change_queue_depth",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499775040,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_about_to_do",
        "drivers/ata/libata-eh.c:ata_eh_detach_dev",
        "drivers/ata/libata-eh.c:__ata_eh_qc_complete",
        "drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-eh.c:ata_port_wait_eh",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499790596,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd",
        "drivers/ata/libata-sff.c:ata_bmdma_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499806016,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/ata/libata-pmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499812856,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499839340,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/ata/libahci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libahci.c:ahci_single_level_irq_intr",
        "drivers/ata/libahci.c:ahci_multi_irqs_intr_hard",
        "drivers/ata/libahci.c:ahci_transmit_led_message",
        "drivers/ata/libahci.c:ahci_sw_activity_blink",
        "drivers/ata/libahci.c:ahci_store_em_buffer",
        "drivers/ata/libahci.c:ahci_read_em_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499855792,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_release",
        "drivers/gpu/vga/vgaarb.c:vga_arb_open",
        "drivers/gpu/vga/vgaarb.c:vga_arb_read",
        "drivers/gpu/vga/vgaarb.c:vga_client_register",
        "drivers/gpu/vga/vgaarb.c:__vga_set_legacy_decoding",
        "drivers/gpu/vga/vgaarb.c:vga_put",
        "drivers/gpu/vga/vgaarb.c:vga_tryget",
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499875392,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_bus_lock",
        "drivers/spi/spi.c:spi_async_locked",
        "drivers/spi/spi.c:spi_async",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_split_transfers_maxsize",
        "drivers/spi/spi.c:spi_split_transfers_maxsize",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_stop_queue",
        "drivers/spi/spi.c:spi_start_queue",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_get_next_queued_message",
        "drivers/spi/spi.c:spi_statistics_add_transfer_stats",
        "drivers/spi/spi.c:spi_statistics_transfers_split_maxsize_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo16_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo15_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo14_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo13_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo12_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo11_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo10_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo9_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo8_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo7_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo6_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo5_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo4_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo3_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo2_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo1_show",
        "drivers/spi/spi.c:spi_statistics_transfer_bytes_histo0_show",
        "drivers/spi/spi.c:spi_statistics_bytes_tx_show",
        "drivers/spi/spi.c:spi_statistics_bytes_rx_show",
        "drivers/spi/spi.c:spi_statistics_bytes_show",
        "drivers/spi/spi.c:spi_statistics_spi_async_show",
        "drivers/spi/spi.c:spi_statistics_spi_sync_immediate_show",
        "drivers/spi/spi.c:spi_statistics_spi_sync_show",
        "drivers/spi/spi.c:spi_statistics_timedout_show",
        "drivers/spi/spi.c:spi_statistics_errors_show",
        "drivers/spi/spi.c:spi_statistics_transfers_show",
        "drivers/spi/spi.c:spi_statistics_messages_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499972368,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_device_event",
        "drivers/net/tun.c:tun_peek_len",
        "drivers/net/tun.c:__tun_set_ebpf",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_chr_poll",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/tun.c:tun_queue_purge",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "drivers/net/tun.c:tun_flow_flush",
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/tun.c:tun_napi_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500004436,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500029184,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_close",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_hwtstamp",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500038628,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/net/ethernet/freescale/fec_ptp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_settime",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_gettime",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjtime",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500049428,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/net/ethernet/freescale/fman/fman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500088956,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom",
        "drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_nwayreset",
        "drivers/net/ethernet/smsc/smc91x.c:smc_open",
        "drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list",
        "drivers/net/ethernet/smsc/smc91x.c:smc_timeout",
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure",
        "drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt",
        "drivers/net/ethernet/smsc/smc91x.c:smc_shutdown",
        "drivers/net/ethernet/smsc/smc91x.c:smc_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500117132,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel",
        "drivers/net/ppp/ppp_generic.c:find_compressor",
        "drivers/net/ppp/ppp_generic.c:ppp_unregister_compressor",
        "drivers/net/ppp/ppp_generic.c:ppp_register_compressor",
        "drivers/net/ppp/ppp_generic.c:ppp_ccp_closed",
        "drivers/net/ppp/ppp_generic.c:ppp_ccp_closed",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/net/ppp/ppp_generic.c:ppp_unregister_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_unregister_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_input_error",
        "drivers/net/ppp/ppp_generic.c:ppp_input",
        "drivers/net/ppp/ppp_generic.c:ppp_push",
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_get_stats64",
        "drivers/net/ppp/ppp_generic.c:ppp_get_stats64",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_poll",
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500154780,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_tx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500218412,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hub.c:hub_ioctl",
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hub.c:usb_hub_clear_tt_buffer",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500247812,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:usb_hcd_synchronize_unlinks",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh",
        "drivers/usb/core/hcd.c:usb_hcd_unlink_urb",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:unlink1",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_link_urb_to_ep",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/core/hcd.c:rh_call_control",
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500252600,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_unpoison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unanchor_urb",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500259628,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/core/message.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_driver_set_configuration",
        "drivers/usb/core/message.c:driver_set_config_work",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_sg_cancel",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:sg_complete",
        "drivers/usb/core/message.c:sg_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500277512,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_match_dynamic_id",
        "drivers/usb/core/driver.c:remove_id_store",
        "drivers/usb/core/driver.c:usb_store_new_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500309904,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:destroy_async_on_interface",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:async_getcompleted",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:usbdev_vm_open",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500347568,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:usb_remove_phy",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/usb/phy/phy.c:usb_get_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500368716,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr",
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500403596,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_reset",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume",
        "drivers/usb/dwc2/hcd.c:dwc2_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500425000,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/dwc2/hcd_intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500431248,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500436996,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500445948,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:usb_amd_dev_put",
        "drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info",
        "drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500500108,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_remove_device",
        "drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable",
        "drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_silence_controller",
        "drivers/usb/host/ehci-hcd.c:ehci_silence_controller",
        "drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store",
        "drivers/usb/host/ehci-hcd.c:sitd_submit",
        "drivers/usb/host/ehci-hcd.c:itd_submit",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete",
        "drivers/usb/host/ehci-hcd.c:set_owner",
        "drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func",
        "drivers/usb/host/ehci-hcd.c:ehci_halt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500534460,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-hcd.c:ohci_shutdown",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:finish_urb",
        "drivers/usb/host/ohci-hcd.c:fill_registers_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_periodic_buffer",
        "drivers/usb/host/ohci-hcd.c:fill_async_buffer",
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_resume",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500554148,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_resume",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable",
        "drivers/usb/host/uhci-hcd.c:uhci_rh_resume",
        "drivers/usb/host/uhci-hcd.c:uhci_rh_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_start",
        "drivers/usb/host/uhci-hcd.c:uhci_irq",
        "drivers/usb/host/uhci-hcd.c:wakeup_rh",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_status_data",
        "drivers/usb/host/uhci-hcd.c:uhci_giveback_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_fsbr_timeout",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500575160,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_change_max_exit_latency",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_disable_slot",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500653308,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500669736,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500690540,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init",
        "drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_exit",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500693320,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_port_activate",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_chars_in_buffer",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_write_room",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_put_char",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_write",
        "drivers/usb/host/xhci-dbgtty.c:dbc_write_complete",
        "drivers/usb/host/xhci-dbgtty.c:dbc_read_complete",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_rx",
        "drivers/usb/host/xhci-dbgtty.c:dbc_start_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500706968,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500718316,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:serio_interrupt",
        "drivers/input/serio/serio.c:serio_close",
        "drivers/input/serio/serio.c:serio_open",
        "drivers/input/serio/serio.c:serio_open",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/serio/serio.c:serio_destroy_port",
        "drivers/input/serio/serio.c:serio_remove_pending_events",
        "drivers/input/serio/serio.c:serio_queue_event",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/serio/serio.c:serio_handle_event",
        "drivers/input/serio/serio.c:serio_remove_duplicate_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500724532,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/input/serio/libps2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_sendbyte",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500742212,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:__input_unregister_device",
        "drivers/input/input.c:input_dev_poweroff",
        "drivers/input/input.c:input_dev_freeze",
        "drivers/input/input.c:input_dev_resume",
        "drivers/input/input.c:input_dev_suspend",
        "drivers/input/input.c:input_reset_device",
        "drivers/input/input.c:input_set_keycode",
        "drivers/input/input.c:input_get_keycode",
        "drivers/input/input.c:input_inject_event",
        "drivers/input/input.c:input_repeat_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500752416,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/input/ff-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/ff-core.c:erase_effect",
        "drivers/input/ff-core.c:erase_effect",
        "drivers/input/ff-core.c:input_ff_upload"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500756384,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_cleanup",
        "drivers/input/mousedev.c:mousedev_read",
        "drivers/input/mousedev.c:mousedev_write",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/mousedev.c:mousedev_notify_readers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500762904,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_cleanup",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_handle_get_val",
        "drivers/input/evdev.c:evdev_read",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_pass_values"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500784424,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper",
        "drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper",
        "drivers/input/keyboard/atkbd.c:atkbd_reconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_reconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/input/keyboard/atkbd.c:atkbd_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500790324,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/input/misc/uinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/misc/uinput.c:uinput_read",
        "drivers/input/misc/uinput.c:uinput_destroy_device",
        "drivers/input/misc/uinput.c:uinput_request_reserve_slot",
        "drivers/input/misc/uinput.c:uinput_request_reserve_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500811588,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_handle_legacy_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500815776,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/rtc/dev.c:rtc_dev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500829108,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/rtc/rtc-sun6i.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_getalarm",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_setaie",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_alarmirq",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500867984,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:put_i2c_dev",
        "drivers/i2c/i2c-dev.c:i2c_dev_get_by_minor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500929244,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pps/pps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pps/pps.c:pps_cdev_compat_ioctl",
        "drivers/pps/pps.c:pps_cdev_ioctl",
        "drivers/pps/pps.c:pps_cdev_ioctl",
        "drivers/pps/pps.c:pps_cdev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500930580,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/pps/kapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pps/kapi.c:pps_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500934028,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500938356,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/ptp/ptp_chardev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_chardev.c:ptp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500940792,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/ptp/ptp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_sysfs.c:extts_fifo_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500954884,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_changed",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work",
        "drivers/power/supply/power_supply_core.c:power_supply_changed_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501000064,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:reset_store",
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show",
        "drivers/thermal/thermal_sysfs.c:total_trans_show",
        "drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501040808,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/watchdog/watchdog_pretimeout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_governor",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_notify_pretimeout",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set",
        "drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501100068,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_setup_cluster",
        "drivers/md/md.c:unregister_md_cluster_operations",
        "drivers/md/md.c:register_md_cluster_operations",
        "drivers/md/md.c:unregister_md_personality",
        "drivers/md/md.c:register_md_personality",
        "drivers/md/md.c:md_seq_next",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:md_attr_store",
        "drivers/md/md.c:md_attr_show",
        "drivers/md/md.c:max_sync_store",
        "drivers/md/md.c:min_sync_store",
        "drivers/md/md.c:level_show",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_find",
        "drivers/md/md.c:md_flush_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501127824,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:behind_writes_used_show",
        "drivers/md/md-bitmap.c:can_clear_show",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_destroy",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_checkpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501170964,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_from_kobject",
        "drivers/md/dm.c:dm_uevent_add",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_hold",
        "drivers/md/dm.c:dm_get_md",
        "drivers/md/dm.c:event_callback",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:free_minor",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:queue_io",
        "drivers/md/dm.c:dm_cancel_deferred_remove",
        "drivers/md/dm.c:dm_lock_for_deletion",
        "drivers/md/dm.c:dm_blk_close",
        "drivers/md/dm.c:dm_blk_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501213092,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:do_work",
        "drivers/md/dm-kcopyd.c:process_jobs",
        "drivers/md/dm-kcopyd.c:process_jobs",
        "drivers/md/dm-kcopyd.c:run_io_job",
        "drivers/md/dm-kcopyd.c:complete_io",
        "drivers/md/dm-kcopyd.c:push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501219216,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc",
        "drivers/md/dm-stats.c:free_shared_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501253484,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/ghes_edac.c:ghes_edac_unregister",
        "drivers/edac/ghes_edac.c:ghes_edac_register",
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501296160,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501310188,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501329012,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501332928,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/cpuidle/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/sysfs.c:show_driver_name",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501358952,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_sw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_hw_reset",
        "drivers/mmc/core/core.c:mmc_detach_bus",
        "drivers/mmc/core/core.c:mmc_detach_bus",
        "drivers/mmc/core/core.c:mmc_attach_bus",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:__mmc_claim_host",
        "drivers/mmc/core/core.c:__mmc_claim_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501431480,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_rw_wait_cond",
        "drivers/mmc/core/block.c:mmc_blk_mq_req_done",
        "drivers/mmc/core/block.c:mmc_blk_mq_req_done",
        "drivers/mmc/core/block.c:mmc_blk_mq_post_req",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501444656,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/mmc/core/queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/queue.c:mmc_mq_queue_rq",
        "drivers/mmc/core/queue.c:mmc_mq_queue_rq",
        "drivers/mmc/core/queue.c:mmc_mq_recovery_handler",
        "drivers/mmc/core/queue.c:mmc_mq_timed_out",
        "drivers/mmc/core/queue.c:mmc_cqe_recovery_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501453424,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_runtime_resume",
        "drivers/mmc/host/mmci.c:mmci_runtime_suspend",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/mmc/host/mmci.c:mmci_request",
        "drivers/mmc/host/mmci.c:mmci_irq",
        "drivers/mmc/host/mmci.c:mmci_card_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501469924,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/leds/led-triggers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501479572,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/firmware/arm_sdei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_sdei.c:sdei_device_thaw",
        "drivers/firmware/arm_sdei.c:sdei_device_freeze",
        "drivers/firmware/arm_sdei.c:sdei_cpuhp_up",
        "drivers/firmware/arm_sdei.c:sdei_cpuhp_down",
        "drivers/firmware/arm_sdei.c:sdei_event_register",
        "drivers/firmware/arm_sdei.c:sdei_event_disable",
        "drivers/firmware/arm_sdei.c:sdei_event_enable",
        "drivers/firmware/arm_sdei.c:sdei_event_destroy",
        "drivers/firmware/arm_sdei.c:sdei_event_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501486416,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/firmware/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/memmap.c:do_raw_spin_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501500144,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/firmware/ti_sci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/ti_sci.c:ti_sci_release_resource",
        "drivers/firmware/ti_sci.c:ti_sci_get_free_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501517640,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/firmware/arm_scmi/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/bus.c:scmi_protocol_unregister",
        "drivers/firmware/arm_scmi/bus.c:scmi_protocol_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501521996,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503915620,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501578732,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_read",
        "drivers/clocksource/sh_cmt.c:sh_cmt_stop",
        "drivers/clocksource/sh_cmt.c:sh_cmt_start",
        "drivers/clocksource/sh_cmt.c:sh_cmt_set_next",
        "drivers/clocksource/sh_cmt.c:sh_cmt_start_stop_ch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501582716,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501608092,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_update_property",
        "drivers/of/base.c:of_remove_property",
        "drivers/of/base.c:of_add_property",
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_match_node",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_node_opts_by_path",
        "drivers/of/base.c:of_get_next_cpu_node",
        "drivers/of/base.c:of_get_next_available_child",
        "drivers/of/base.c:of_get_next_child",
        "drivers/of/base.c:of_get_next_parent",
        "drivers/of/base.c:of_get_parent",
        "drivers/of/base.c:of_device_is_available",
        "drivers/of/base.c:of_device_is_compatible",
        "drivers/of/base.c:of_find_all_nodes",
        "drivers/of/base.c:of_find_property",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_free_phandle_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501628684,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/of/dynamic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/dynamic.c:__of_changeset_entry_apply",
        "drivers/of/dynamic.c:of_detach_node",
        "drivers/of/dynamic.c:of_attach_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501652420,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/of/resolver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/resolver.c:of_resolve_phandles"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501668132,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/mailbox/mailbox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/mailbox.c:mbox_request_channel",
        "drivers/mailbox/mailbox.c:mbox_send_message",
        "drivers/mailbox/mailbox.c:msg_submit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501672776,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_mbox_free_channel",
        "drivers/mailbox/pcc.c:pcc_mbox_request_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501674760,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/mailbox/bcm2835-mailbox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/bcm2835-mailbox.c:bcm2835_last_tx_done",
        "drivers/mailbox/bcm2835-mailbox.c:bcm2835_send_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501685852,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501724684,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_unregister_notifier_all",
        "drivers/extcon/extcon.c:extcon_register_notifier_all",
        "drivers/extcon/extcon.c:extcon_unregister_notifier",
        "drivers/extcon/extcon.c:extcon_register_notifier",
        "drivers/extcon/extcon.c:extcon_set_property",
        "drivers/extcon/extcon.c:extcon_get_property",
        "drivers/extcon/extcon.c:extcon_set_state",
        "drivers/extcon/extcon.c:extcon_get_state",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/extcon/extcon.c:extcon_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501736016,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/memory/fsl_ifc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/fsl_ifc.c:check_nand_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501749412,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_free",
        "drivers/vme/vme.c:vme_master_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501762436,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_start",
        "drivers/perf/arm-cci.c:cci_pmu_disable",
        "drivers/perf/arm-cci.c:cci_pmu_enable",
        "drivers/perf/arm-cci.c:pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501769288,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_xp_dt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501794384,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_start",
        "drivers/perf/qcom_l2_pmu.c:get_l2_indirect_reg",
        "drivers/perf/qcom_l2_pmu.c:set_l2_indirect_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501807292,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "drivers/perf/xgene_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/xgene_pmu.c:xgene_pmu_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501831584,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501877324,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_common_release",
        "net/core/sock.c:release_sock",
        "net/core/sock.c:lock_sock_nested",
        "net/core/sock.c:__sk_flush_backlog",
        "net/core/sock.c:__release_sock",
        "net/core/sock.c:__lock_sock",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501887840,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501902944,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_dequeue_err_skb",
        "net/core/skbuff.c:skb_append",
        "net/core/skbuff.c:skb_unlink",
        "net/core/skbuff.c:skb_queue_tail",
        "net/core/skbuff.c:skb_queue_head",
        "net/core/skbuff.c:skb_dequeue_tail",
        "net/core/skbuff.c:skb_dequeue",
        "net/core/skbuff.c:sock_zerocopy_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501938464,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__sk_queue_drop_skb",
        "net/core/datagram.c:__skb_try_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501949192,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/gen_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gen_stats.c:gnet_stats_start_copy_compat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501950752,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/gen_estimator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/gen_estimator.c:est_fetch_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501957132,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:netns_get",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:get_net_ns_by_pid",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:peernet2id",
        "net/core/net_namespace.c:peernet2id_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502041288,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_set_rx_mode",
        "net/core/dev.c:netif_napi_add",
        "net/core/dev.c:napi_hash_del",
        "net/core/dev.c:process_backlog",
        "net/core/dev.c:flush_backlog",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_add_offload",
        "net/core/dev.c:__dev_remove_pack",
        "net/core/dev.c:dev_add_pack",
        "net/core/dev.c:unlist_netdevice",
        "net/core/dev.c:list_netdevice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502081224,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/dev_addr_lists.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:dev_mc_flush",
        "net/core/dev_addr_lists.c:dev_mc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_mc_sync",
        "net/core/dev_addr_lists.c:__dev_mc_del",
        "net/core/dev_addr_lists.c:__dev_mc_add",
        "net/core/dev_addr_lists.c:dev_mc_add_excl",
        "net/core/dev_addr_lists.c:dev_uc_flush",
        "net/core/dev_addr_lists.c:dev_uc_sync_multiple",
        "net/core/dev_addr_lists.c:dev_uc_sync",
        "net/core/dev_addr_lists.c:dev_uc_del",
        "net/core/dev_addr_lists.c:dev_uc_add",
        "net/core/dev_addr_lists.c:dev_uc_add_excl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502100796,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_for_each_release",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_delete",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_invalidate",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:pneigh_delete",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr",
        "net/core/neighbour.c:neigh_remove_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502144000,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_fdb_dump",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:set_operstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502163832,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_forget_dev",
        "net/core/link_watch.c:__linkwatch_run_queue",
        "net/core/link_watch.c:__linkwatch_run_queue",
        "net/core/link_watch.c:rfc2863_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502235820,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_attach_prog",
        "net/core/sock_reuseport.c:reuseport_detach_sock",
        "net/core/sock_reuseport.c:reuseport_add_sock",
        "net/core/sock_reuseport.c:reuseport_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502256640,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_timeout_show",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502266572,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502271988,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/net-procfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502277900,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_data_ready",
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_link_pop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502285148,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:refill_skbs",
        "net/core/netpoll.c:queue_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502291272,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_unregister",
        "net/core/fib_rules.c:fib_rules_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502327628,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe",
        "net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data",
        "net/core/drop_monitor.c:reset_per_cpu_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502334600,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/netprio_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netprio_cgroup.c:net_prio_attach",
        "net/core/netprio_cgroup.c:update_netprio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502335456,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/netclassid_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netclassid_cgroup.c:update_classid_task",
        "net/core/netclassid_cgroup.c:update_classid_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502353052,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_unref",
        "net/core/sock_map.c:sock_map_unref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502371956,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_trap_report",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_nl_port_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502419864,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:__sk_storage_lookup",
        "net/core/bpf_sk_storage.c:selem_link_map",
        "net/core/bpf_sk_storage.c:selem_unlink_map",
        "net/core/bpf_sk_storage.c:selem_unlink_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502452260,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_graft_qdisc",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502456556,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/sched/sch_mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_mq.c:mq_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502464680,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tcf_node_bind",
        "net/sched/sch_api.c:qdisc_class_hash_grow",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:qdisc_set_default",
        "net/sched/sch_api.c:unregister_qdisc",
        "net/sched/sch_api.c:register_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502486808,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_setup_cb_destroy",
        "net/sched/cls_api.c:tc_setup_cb_replace",
        "net/sched/cls_api.c:tc_cls_offload_cnt_update",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_get_next_proto",
        "net/sched/cls_api.c:unregister_tcf_proto_ops",
        "net/sched/cls_api.c:register_tcf_proto_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502505128,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_unregister_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502517536,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/ematch.c:tcf_em_unregister",
        "net/sched/ematch.c:tcf_em_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502538316,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502585552,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_flush_dev",
        "net/ipv4/route.c:rt_add_uncached_list",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:update_or_create_fnhe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502598192,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/inetpeer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inetpeer.c:inet_getpeer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502607344,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502653716,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_hashtables.c:inet_put_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502655620,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502663836,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_add",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502696080,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502768560,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_tsq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502773572,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502800888,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502809712,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_register_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502814164,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del",
        "net/ipv4/tcp_metrics.c:tcp_metrics_flush_all",
        "net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set",
        "net/ipv4/tcp_metrics.c:tcp_get_metrics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502819708,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502824296,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/tcp_ulp.c:tcp_register_ulp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502833956,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_ioctl",
        "net/ipv4/raw.c:raw_unhash_sk",
        "net/ipv4/raw.c:raw_hash_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502852312,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_rehash",
        "net/ipv4/udp.c:udp_lib_rehash",
        "net/ipv4/udp.c:udp_lib_rehash",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:udp_rmem_release",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502877800,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_req_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502889180,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/icmp.c:icmp_global_allow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502918188,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_register_protosw",
        "net/ipv4/af_inet.c:inet_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502936472,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_mcf_seq_next",
        "net/ipv4/igmp.c:igmp_mcf_seq_start",
        "net/ipv4/igmp.c:ip_mc_clear_src",
        "net/ipv4/igmp.c:ip_mc_add_src",
        "net/ipv4/igmp.c:ip_mc_del_src",
        "net/ipv4/igmp.c:igmp_group_added",
        "net/ipv4/igmp.c:__igmp_group_dropped",
        "net/ipv4/igmp.c:__igmp_group_dropped",
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_clear_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmpv3_del_delrec",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmpv3_send_report",
        "net/ipv4/igmp.c:igmp_stop_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502969040,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:ip_fib_check_default",
        "net/ipv4/fib_semantics.c:fib_release_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502995724,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frags_free_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503004236,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_unhash",
        "net/ipv4/ping.c:ping_get_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503030496,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/sysctl_net_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range",
        "net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503050548,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:ipmr_expire_process",
        "net/ipv4/ipmr.c:vif_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503070528,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_table_dump",
        "net/ipv4/ipmr_base.c:mr_mfc_seq_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503084940,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503089816,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove",
        "net/ipv4/cipso_ipv4.c:cipso_v4_doi_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_add",
        "net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503121336,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_fini",
        "net/xfrm/xfrm_policy.c:xfrm_if_register_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_register_afinfo",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy",
        "net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_policy_walk",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_flush",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_policy_requeue",
        "net/xfrm/xfrm_policy.c:xfrm_hash_rebuild",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503152728,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_state_register_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_register_km",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_state.c:xfrm_state_walk",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_find_acq_byseq",
        "net/xfrm/xfrm_state.c:xfrm_find_acq",
        "net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:xfrm_state_add",
        "net/xfrm/xfrm_state.c:xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_stateonly_find",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_sad_getinfo",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_dev_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_flush",
        "net/xfrm/xfrm_state.c:xfrm_state_delete",
        "net/xfrm/xfrm_state.c:__xfrm_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503175916,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/xfrm/xfrm_input.c:xfrm_input_register_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503181288,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503191316,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:xfrm_dev_backlog",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503199748,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_seq_show",
        "net/unix/af_unix.c:unix_dgram_poll",
        "net/unix/af_unix.c:unix_inq_len",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_accept",
        "net/unix/af_unix.c:unix_accept",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_bind",
        "net/unix/af_unix.c:unix_bind",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_find_other",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_dgram_peer_wake_me",
        "net/unix/af_unix.c:unix_dgram_peer_wake_disconnect",
        "net/unix/af_unix.c:unix_peer_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503217072,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/unix/garbage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/garbage.c:unix_gc",
        "net/unix/garbage.c:unix_gc",
        "net/unix/garbage.c:scan_inflight"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503219268,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/unix/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/scm.c:unix_notinflight",
        "net/unix/scm.c:unix_inflight"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503223372,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_register_protosw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503230076,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/anycast.c:ipv6_anycast_cleanup",
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/anycast.c:__ipv6_dev_ac_inc",
        "net/ipv6/anycast.c:__ipv6_dev_ac_inc",
        "net/ipv6/anycast.c:ipv6_del_acaddr_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503307048,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_disable_policy_idev",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_run",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_work",
        "net/ipv6/addrconf.c:addrconf_dad_start",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:ipv6_generate_stable_address",
        "net/ipv6/addrconf.c:add_addr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:manage_tempaddrs",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:check_cleanup_prefix_route",
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503312452,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/addrlabel.c:ip6addrlbl_net_exit",
        "net/ipv6/addrlabel.c:ip6addrlbl_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503335392,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:__ip6_del_rt",
        "net/ipv6/route.c:ip6_sk_update_pmtu",
        "net/ipv6/route.c:fib6_table_lookup",
        "net/ipv6/route.c:fib6_nh_remove_exception",
        "net/ipv6/route.c:fib6_nh_flush_exceptions",
        "net/ipv6/route.c:rt6_insert_exception",
        "net/ipv6/route.c:rt6_insert_exception",
        "net/ipv6/route.c:__ip6_ins_rt",
        "net/ipv6/route.c:rt6_uncached_list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503369196,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:ipv6_route_seq_next",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/ip6_fib.c:fib6_run_gc",
        "net/ipv6/ip6_fib.c:__fib6_clean_all",
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub",
        "net/ipv6/ip6_fib.c:fib6_tables_dump",
        "net/ipv6/ip6_fib.c:fib6_walker_unlink",
        "net/ipv6/ip6_fib.c:fib6_walker_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503385280,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ip6_ra_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503431908,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503444996,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503462084,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_mcf_seq_next",
        "net/ipv6/mcast.c:igmp6_mcf_seq_start",
        "net/ipv6/mcast.c:ipv6_mc_destroy_dev",
        "net/ipv6/mcast.c:ipv6_mc_destroy_dev",
        "net/ipv6/mcast.c:ipv6_mc_init_dev",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_leave_src",
        "net/ipv6/mcast.c:ip6_mc_add_src",
        "net/ipv6/mcast.c:ip6_mc_del_src",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:mld_send_report",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_chk_mcast_addr",
        "net/ipv6/mcast.c:__ipv6_dev_mc_dec",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:ip6_mc_msfilter",
        "net/ipv6/mcast.c:ip6_mc_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503482744,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ip6_frag_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503498780,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503521024,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get",
        "net/ipv6/ip6_flowlabel.c:fl6_renew",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:fl6_free_socklist",
        "net/ipv6/ip6_flowlabel.c:ip6_fl_gc",
        "net/ipv6/ip6_flowlabel.c:fl_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503551688,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_sk_done",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/ipv6/ip6mr.c:mif6_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503562156,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503584712,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_opt_getattr",
        "net/ipv6/calipso.c:calipso_doi_remove",
        "net/ipv6/calipso.c:calipso_doi_add",
        "net/ipv6/calipso.c:calipso_cache_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503615240,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503639016,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/packet/af_packet.c:packet_ioctl",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_getsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:__fanout_set_data_bpf",
        "net/packet/af_packet.c:__fanout_link",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503679080,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503690328,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503704676,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_blocked",
        "net/rfkill/core.c:rfkill_set_states",
        "net/rfkill/core.c:rfkill_init_sw_state",
        "net/rfkill/core.c:rfkill_set_sw_state",
        "net/rfkill/core.c:rfkill_set_hw_state",
        "net/rfkill/core.c:rfkill_set_block",
        "net/rfkill/core.c:rfkill_set_block",
        "net/rfkill/core.c:rfkill_fill_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503712496,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/rfkill/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/input.c:rfkill_start",
        "net/rfkill/input.c:rfkill_schedule_global_op",
        "net/rfkill/input.c:rfkill_op_handler",
        "net/rfkill/input.c:rfkill_op_handler",
        "net/rfkill/input.c:rfkill_op_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503720932,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask",
        "net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map",
        "net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map",
        "net/dcb/dcbnl.c:dcb_ieee_delapp",
        "net/dcb/dcbnl.c:dcb_ieee_setapp",
        "net/dcb/dcbnl.c:dcb_ieee_getapp_mask",
        "net/dcb/dcbnl.c:dcb_setapp",
        "net/dcb/dcbnl.c:dcb_getapp",
        "net/dcb/dcbnl.c:dcbnl_cee_fill",
        "net/dcb/dcbnl.c:dcbnl_ieee_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503738508,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/switchdev/switchdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/switchdev/switchdev.c:switchdev_deferred_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503750588,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503751772,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ncsi/ncsi-aen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503759504,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev",
        "net/ncsi/ncsi-manage.c:ncsi_reset_dev",
        "net/ncsi/ncsi-manage.c:ncsi_reset_dev",
        "net/ncsi/ncsi-manage.c:ncsi_reset_dev",
        "net/ncsi/ncsi-manage.c:ncsi_reset_dev",
        "net/ncsi/ncsi-manage.c:ncsi_stop_dev",
        "net/ncsi/ncsi-manage.c:ncsi_kick_channels",
        "net/ncsi/ncsi-manage.c:ncsi_kick_channels",
        "net/ncsi/ncsi-manage.c:ncsi_kick_channels",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_process_next_channel",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_choose_active_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel",
        "net/ncsi/ncsi-manage.c:ncsi_suspend_channel",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_alloc_request",
        "net/ncsi/ncsi-manage.c:ncsi_remove_package",
        "net/ncsi/ncsi-manage.c:ncsi_remove_package",
        "net/ncsi/ncsi-manage.c:ncsi_remove_package",
        "net/ncsi/ncsi-manage.c:ncsi_add_package",
        "net/ncsi/ncsi-manage.c:ncsi_add_channel",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_report_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503776340,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503783660,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xsk.c:xsk_release",
        "net/xdp/xsk.c:xsk_destruct_skb",
        "net/xdp/xsk.c:xsk_generic_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503790840,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_del_sk_umem",
        "net/xdp/xdp_umem.c:xdp_add_sk_umem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503805828,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/dec_and_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503820420,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/flex_proportions.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503823608,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_destroy",
        "lib/idr.c:ida_free",
        "lib/idr.c:ida_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503827484,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/klist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/klist.c:klist_next",
        "lib/klist.c:klist_prev",
        "lib/klist.c:klist_remove",
        "lib/klist.c:klist_put",
        "lib/klist.c:klist_release",
        "lib/klist.c:klist_add_before",
        "lib/klist.c:klist_add_behind",
        "lib/klist.c:klist_add_tail",
        "lib/klist.c:klist_add_head"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503830696,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/kobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobj_ns_drop",
        "lib/kobject.c:kobj_ns_initial",
        "lib/kobject.c:kobj_ns_netlink",
        "lib/kobject.c:kobj_ns_grab_current",
        "lib/kobject.c:kobj_ns_current_may_mount",
        "lib/kobject.c:kobj_ns_type_register",
        "lib/kobject.c:kset_find_obj",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobject_add_internal",
        "lib/kobject.c:kobj_kset_leave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503848328,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/ratelimit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503897192,
      "name": "__cmpxchg_case_acq_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:121",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_destroy",
        "lib/xarray.c:xa_clear_mark",
        "lib/xarray.c:xa_set_mark",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:xa_store",
        "lib/xarray.c:xa_erase",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem",
        "lib/xarray.c:__xas_nomem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491864432,
      "name": "__cmpxchg_case_acq_32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
u32 __cmpxchg_case_acq_32(volatile void * ptr, u32 old, u32 new)
```
</details>
</li>
</ul>

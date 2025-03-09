# Function: <code>__my_cpu_offset</code>

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
long unsigned int __my_cpu_offset()
```

```json
{
  "name": "__my_cpu_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490176284,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "init/main.c:do_one_initcall",
        "init/main.c:perf_trace_initcall_finish",
        "init/main.c:perf_trace_initcall_start",
        "init/main.c:perf_trace_initcall_level",
        "init/main.c:rest_init"
      ],
      "caller_func": [
        "init/main.c:trace_initcall_level"
      ]
    },
    {
      "addr": 18446603336490178676,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "init/calibrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/calibrate.c:calibrate_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490181396,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/debug-monitors.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/debug-monitors.c:disable_debug_monitors",
        "arch/arm64/kernel/debug-monitors.c:disable_debug_monitors",
        "arch/arm64/kernel/debug-monitors.c:enable_debug_monitors",
        "arch/arm64/kernel/debug-monitors.c:enable_debug_monitors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490184268,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490190832,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end",
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end",
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end",
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end",
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin",
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin",
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin",
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin",
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin",
        "arch/arm64/kernel/fpsimd.c:fpsimd_flush_cpu_state",
        "arch/arm64/kernel/fpsimd.c:fpsimd_bind_state_to_cpu",
        "arch/arm64/kernel/fpsimd.c:fpsimd_bind_task_to_cpu",
        "arch/arm64/kernel/fpsimd.c:fpsimd_bind_task_to_cpu",
        "arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch",
        "arch/arm64/kernel/fpsimd.c:fpsimd_save",
        "arch/arm64/kernel/fpsimd.c:fpsimd_save",
        "arch/arm64/kernel/fpsimd.c:task_fpsimd_load"
      ],
      "caller_func": [
        "arch/arm64/kernel/fpsimd.c:sve_verify_vq_map",
        "arch/arm64/kernel/fpsimd.c:sve_verify_vq_map"
      ]
    },
    {
      "addr": 18446603336490194148,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/process.c:__switch_to",
        "arch/arm64/kernel/process.c:arch_cpu_idle",
        "arch/arm64/kernel/process.c:arch_cpu_idle",
        "arch/arm64/kernel/process.c:arch_cpu_idle",
        "arch/arm64/kernel/process.c:arch_cpu_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490217260,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:syscall_trace_exit",
        "arch/arm64/kernel/ptrace.c:syscall_trace_enter",
        "arch/arm64/kernel/ptrace.c:regs_get_kernel_stack_nth",
        "arch/arm64/kernel/ptrace.c:perf_trace_sys_exit",
        "arch/arm64/kernel/ptrace.c:perf_trace_sys_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490236452,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/stacktrace.c:unwind_frame",
        "arch/arm64/kernel/stacktrace.c:unwind_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490244156,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/traps.c:do_serror",
        "arch/arm64/kernel/traps.c:do_serror"
      ],
      "caller_func": [
        "arch/arm64/kernel/traps.c:arm64_serror_panic",
        "arch/arm64/kernel/traps.c:handle_bad_stack",
        "arch/arm64/kernel/traps.c:handle_bad_stack",
        "arch/arm64/kernel/traps.c:bad_mode"
      ]
    },
    {
      "addr": 18446603336490254712,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/cpuinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpuinfo.c:cpuinfo_store_cpu",
        "arch/arm64/kernel/cpuinfo.c:cpuinfo_store_cpu",
        "arch/arm64/kernel/cpuinfo.c:__cpuinfo_store_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490258000,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/cpu_errata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpu_errata.c:has_ssbd_mitigation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490262932,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/cpufeature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings"
      ],
      "caller_func": [
        "arch/arm64/kernel/cpufeature.c:check_local_cpu_capabilities",
        "arch/arm64/kernel/cpufeature.c:verify_local_elf_hwcaps",
        "arch/arm64/kernel/cpufeature.c:verify_local_cpu_caps"
      ]
    },
    {
      "addr": 18446603336490267208,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/alternative.c:apply_boot_alternatives"
      ]
    },
    {
      "addr": 18446603336490268920,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cacheinfo.c:_populate_cache_leaves",
        "arch/arm64/kernel/cacheinfo.c:_init_cache_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490276052,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:cpus_are_stuck_in_kernel",
        "arch/arm64/kernel/smp.c:crash_smp_send_stop",
        "arch/arm64/kernel/smp.c:crash_smp_send_stop",
        "arch/arm64/kernel/smp.c:crash_smp_send_stop",
        "arch/arm64/kernel/smp.c:smp_send_stop",
        "arch/arm64/kernel/smp.c:smp_send_stop",
        "arch/arm64/kernel/smp.c:smp_send_stop",
        "arch/arm64/kernel/smp.c:smp_send_stop",
        "arch/arm64/kernel/smp.c:smp_send_stop",
        "arch/arm64/kernel/smp.c:tick_broadcast",
        "arch/arm64/kernel/smp.c:smp_send_reschedule",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "arch/arm64/kernel/smp.c:arch_irq_work_raise",
        "arch/arm64/kernel/smp.c:arch_irq_work_raise",
        "arch/arm64/kernel/smp.c:arch_send_wakeup_ipi_mask",
        "arch/arm64/kernel/smp.c:arch_send_call_function_single_ipi",
        "arch/arm64/kernel/smp.c:arch_send_call_function_ipi_mask",
        "arch/arm64/kernel/smp.c:__cpu_disable",
        "arch/arm64/kernel/smp.c:perf_trace_ipi_handler",
        "arch/arm64/kernel/smp.c:perf_trace_ipi_raise"
      ],
      "caller_func": [
        "arch/arm64/kernel/smp.c:crash_smp_send_stop",
        "arch/arm64/kernel/smp.c:local_cpu_stop",
        "arch/arm64/kernel/smp.c:smp_prepare_cpus",
        "arch/arm64/kernel/smp.c:smp_prepare_cpus",
        "arch/arm64/kernel/smp.c:smp_prepare_boot_cpu",
        "arch/arm64/kernel/smp.c:cpu_die_early",
        "arch/arm64/kernel/smp.c:cpu_die"
      ]
    },
    {
      "addr": 18446603336490277532,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490305632,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/perf_event.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/perf_event.c:armv8pmu_handle_irq",
        "arch/arm64/kernel/perf_event.c:armv8pmu_stop",
        "arch/arm64/kernel/perf_event.c:armv8pmu_start",
        "arch/arm64/kernel/perf_event.c:armv8pmu_disable_event",
        "arch/arm64/kernel/perf_event.c:armv8pmu_enable_event"
      ],
      "caller_func": [
        "arch/arm64/kernel/perf_event.c:armv8pmu_write_counter",
        "arch/arm64/kernel/perf_event.c:armv8pmu_read_counter"
      ]
    },
    {
      "addr": 18446603336490311296,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_reset",
        "arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_reset",
        "arch/arm64/kernel/hw_breakpoint.c:reinstall_suspended_bps",
        "arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler",
        "arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler",
        "arch/arm64/kernel/hw_breakpoint.c:breakpoint_handler",
        "arch/arm64/kernel/hw_breakpoint.c:breakpoint_handler",
        "arch/arm64/kernel/hw_breakpoint.c:toggle_bp_registers",
        "arch/arm64/kernel/hw_breakpoint.c:toggle_bp_registers",
        "arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_control",
        "arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490314156,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/suspend.c:__cpu_suspend_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490315724,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpuidle.c:arm_cpuidle_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490317380,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/kgdb.c:kgdb_arch_handle_exception"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490323844,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/armv8_deprecated.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/armv8_deprecated.c:cp15barrier_handler",
        "arch/arm64/kernel/armv8_deprecated.c:cp15barrier_handler",
        "arch/arm64/kernel/armv8_deprecated.c:cp15barrier_handler",
        "arch/arm64/kernel/armv8_deprecated.c:swp_handler",
        "arch/arm64/kernel/armv8_deprecated.c:swp_handler",
        "arch/arm64/kernel/armv8_deprecated.c:perf_trace_instruction_emulation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490325068,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/acpi.c:apei_claim_sea",
        "arch/arm64/kernel/acpi.c:apei_claim_sea"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490325932,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/acpi_parking_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490327984,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/machine_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/machine_kexec.c:machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503950868,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/sdei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/sdei.c:__sdei_handler",
        "arch/arm64/kernel/sdei.c:__sdei_handler",
        "arch/arm64/kernel/sdei.c:_on_sdei_stack",
        "arch/arm64/kernel/sdei.c:_on_sdei_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503951476,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kernel/probes/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler",
        "arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler",
        "arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler",
        "arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler",
        "arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler",
        "arch/arm64/kernel/probes/kprobes.c:kprobe_single_step_handler",
        "arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler",
        "arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler",
        "arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler",
        "arch/arm64/kernel/probes/kprobes.c:arch_simulate_insn",
        "arch/arm64/kernel/probes/kprobes.c:post_kprobe_handler",
        "arch/arm64/kernel/probes/kprobes.c:post_kprobe_handler",
        "arch/arm64/kernel/probes/kprobes.c:post_kprobe_handler",
        "arch/arm64/kernel/probes/kprobes.c:trampoline_probe_handler",
        "arch/arm64/kernel/probes/kprobes.c:trampoline_probe_handler",
        "arch/arm64/kernel/probes/kprobes.c:trampoline_probe_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490160740,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/fault.c:do_debug_exception",
        "arch/arm64/mm/fault.c:do_debug_exception",
        "arch/arm64/mm/fault.c:do_sp_pc_abort",
        "arch/arm64/mm/fault.c:do_el0_ia_bp_hardening",
        "arch/arm64/mm/fault.c:do_el0_irq_bp_hardening",
        "arch/arm64/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490351712,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/context.c:check_and_switch_context"
      ],
      "caller_func": [
        "arch/arm64/mm/context.c:verify_cpu_asid_bits",
        "arch/arm64/mm/context.c:get_cpu_asid_bits"
      ]
    },
    {
      "addr": 18446603336490388132,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:hardware_disable_nolock",
        "virt/kvm/kvm_main.c:hardware_enable_nolock",
        "virt/kvm/kvm_main.c:kvm_vcpu_ioctl",
        "virt/kvm/kvm_main.c:kvm_vcpu_kick",
        "virt/kvm/kvm_main.c:kvm_vcpu_block",
        "virt/kvm/kvm_main.c:kvm_vcpu_block",
        "virt/kvm/kvm_main.c:kvm_vcpu_block",
        "virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask",
        "virt/kvm/kvm_main.c:vcpu_load",
        "virt/kvm/kvm_main.c:perf_trace_kvm_halt_poll_ns",
        "virt/kvm/kvm_main.c:perf_trace_kvm_age_page",
        "virt/kvm/kvm_main.c:perf_trace_kvm_fpu",
        "virt/kvm/kvm_main.c:perf_trace_kvm_mmio",
        "virt/kvm/kvm_main.c:perf_trace_kvm_ack_irq",
        "virt/kvm/kvm_main.c:perf_trace_kvm_set_irq",
        "virt/kvm/kvm_main.c:perf_trace_kvm_vcpu_wakeup",
        "virt/kvm/kvm_main.c:perf_trace_kvm_userspace_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490421884,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "virt/kvm/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/eventfd.c:kvm_notify_acked_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490441036,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:cpu_hyp_reinit",
        "virt/kvm/arm/arm.c:cpu_hyp_reinit",
        "virt/kvm/arm/arm.c:cpu_hyp_reinit",
        "virt/kvm/arm/arm.c:cpu_hyp_reinit",
        "virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_put",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_load",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_load",
        "virt/kvm/arm/arm.c:kvm_arm_get_running_vcpu",
        "virt/kvm/arm/arm.c:perf_trace_kvm_timer_emulate",
        "virt/kvm/arm/arm.c:perf_trace_kvm_timer_hrtimer_expire",
        "virt/kvm/arm/arm.c:perf_trace_kvm_timer_restore_state",
        "virt/kvm/arm/arm.c:perf_trace_kvm_timer_save_state",
        "virt/kvm/arm/arm.c:perf_trace_kvm_get_timer_map",
        "virt/kvm/arm/arm.c:perf_trace_kvm_timer_update_irq",
        "virt/kvm/arm/arm.c:perf_trace_kvm_toggle_cache",
        "virt/kvm/arm/arm.c:perf_trace_kvm_set_way_flush",
        "virt/kvm/arm/arm.c:perf_trace_kvm_test_age_hva",
        "virt/kvm/arm/arm.c:perf_trace_kvm_age_hva",
        "virt/kvm/arm/arm.c:perf_trace_kvm_set_spte_hva",
        "virt/kvm/arm/arm.c:perf_trace_kvm_unmap_hva_range",
        "virt/kvm/arm/arm.c:perf_trace_kvm_mmio_emulate",
        "virt/kvm/arm/arm.c:perf_trace_kvm_irq_line",
        "virt/kvm/arm/arm.c:perf_trace_kvm_access_fault",
        "virt/kvm/arm/arm.c:perf_trace_kvm_guest_fault",
        "virt/kvm/arm/arm.c:perf_trace_kvm_exit",
        "virt/kvm/arm/arm.c:perf_trace_kvm_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490472212,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:kvm_toggle_cache",
        "virt/kvm/arm/mmu.c:kvm_set_way_flush",
        "virt/kvm/arm/mmu.c:kvm_test_age_hva",
        "virt/kvm/arm/mmu.c:kvm_age_hva",
        "virt/kvm/arm/mmu.c:kvm_set_spte_hva",
        "virt/kvm/arm/mmu.c:kvm_unmap_hva_range",
        "virt/kvm/arm/mmu.c:kvm_handle_guest_abort",
        "virt/kvm/arm/mmu.c:kvm_handle_guest_abort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490474752,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "virt/kvm/arm/mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmio.c:io_mem_abort",
        "virt/kvm/arm/mmio.c:io_mem_abort",
        "virt/kvm/arm/mmio.c:kvm_handle_mmio_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490489280,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kvm/handle_exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/handle_exit.c:kvm_handle_wfx",
        "arch/arm64/kvm/handle_exit.c:kvm_handle_wfx",
        "arch/arm64/kvm/handle_exit.c:handle_hvc",
        "arch/arm64/kvm/handle_exit.c:perf_trace_kvm_set_guest_debug",
        "arch/arm64/kvm/handle_exit.c:perf_trace_kvm_sys_access",
        "arch/arm64/kvm/handle_exit.c:perf_trace_kvm_handle_sys_reg",
        "arch/arm64/kvm/handle_exit.c:perf_trace_trap_reg",
        "arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_set_regset",
        "arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_set_dreg32",
        "arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_clear_debug",
        "arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_setup_debug",
        "arch/arm64/kvm/handle_exit.c:perf_trace_kvm_hvc_arm64",
        "arch/arm64/kvm/handle_exit.c:perf_trace_kvm_wfx_arm64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490499088,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kvm/guest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/guest.c:kvm_arch_vcpu_ioctl_set_guest_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490501268,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kvm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/debug.c:kvm_arm_clear_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_clear_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_clear_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_clear_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_init_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490503220,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kvm/reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/reset.c:kvm_reset_vcpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490522116,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kvm/sys_regs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/sys_regs.c:kvm_handle_sys_reg",
        "arch/arm64/kvm/sys_regs.c:perform_access",
        "arch/arm64/kvm/sys_regs.c:trap_xvr",
        "arch/arm64/kvm/sys_regs.c:trap_wcr",
        "arch/arm64/kvm/sys_regs.c:trap_wvr",
        "arch/arm64/kvm/sys_regs.c:trap_bcr",
        "arch/arm64/kvm/sys_regs.c:trap_bvr",
        "arch/arm64/kvm/sys_regs.c:trap_debug_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490529548,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kvm/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/pmu.c:kvm_clr_pmu_events",
        "arch/arm64/kvm/pmu.c:kvm_set_pmu_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490534372,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "virt/kvm/arm/vgic/vgic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq",
        "virt/kvm/arm/vgic/vgic.c:perf_trace_vgic_update_irq_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490552232,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "virt/kvm/arm/vgic/vgic-v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_flush_hwstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490597764,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "virt/kvm/irqchip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/irqchip.c:kvm_set_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490602780,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "virt/kvm/arm/arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load",
        "virt/kvm/arm/arch_timer.c:timer_restore_state",
        "virt/kvm/arm/arch_timer.c:timer_save_state",
        "virt/kvm/arm/arch_timer.c:kvm_hrtimer_expire",
        "virt/kvm/arm/arch_timer.c:get_timer_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490613876,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "arch/arm64/kvm/hyp/switch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/hyp/switch.c:activate_traps_vhe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490634544,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:perf_trace_task_rename",
        "kernel/fork.c:perf_trace_task_newtask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490640576,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:nmi_panic"
      ],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/panic.c:__warn",
        "kernel/panic.c:panic"
      ]
    },
    {
      "addr": 18446603336490651752,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:cpuhp_online_idle",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_kick_ap_work",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_should_run",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:cpuhp_invoke_callback",
        "kernel/cpu.c:perf_trace_cpuhp_exit",
        "kernel/cpu.c:perf_trace_cpuhp_multi_enter",
        "kernel/cpu.c:perf_trace_cpuhp_enter"
      ],
      "caller_func": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:boot_cpu_init",
        "kernel/cpu.c:cpuhp_threads_init"
      ]
    },
    {
      "addr": 18446603336490662704,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:release_task",
        "kernel/exit.c:delayed_put_task_struct"
      ],
      "caller_func": [
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit"
      ]
    },
    {
      "addr": 18446603336490678008,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:ksoftirqd_should_run",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:__raise_softirq_irqoff",
        "kernel/softirq.c:__raise_softirq_irqoff",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__local_bh_enable_ip",
        "kernel/softirq.c:ksoftirqd_running",
        "kernel/softirq.c:wakeup_softirqd",
        "kernel/softirq.c:perf_trace_softirq",
        "kernel/softirq.c:perf_trace_irq_handler_exit",
        "kernel/softirq.c:perf_trace_irq_handler_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490744768,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:send_sigqueue",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:perf_trace_signal_deliver",
        "kernel/signal.c:perf_trace_signal_generate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490775132,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__arm64_sys_getcpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490822704,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu",
        "kernel/workqueue.c:workqueue_congested",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:pwq_activate_delayed_work",
        "kernel/workqueue.c:perf_trace_workqueue_execute_start",
        "kernel/workqueue.c:perf_trace_workqueue_queue_work",
        "kernel/workqueue.c:perf_trace_workqueue_work"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init"
      ]
    },
    {
      "addr": 18446603336490845768,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop",
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490876020,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:cpu_report_death",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/smpboot.c:smpboot_thread_fn"
      ],
      "caller_func": [
        "kernel/smpboot.c:idle_threads_init",
        "kernel/smpboot.c:idle_thread_set_boot_cpu"
      ]
    },
    {
      "addr": 18446603336490878684,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490930336,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:do_sched_yield",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:sched_exec",
        "kernel/sched/core.c:single_task_running",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi",
        "kernel/sched/core.c:perf_trace_sched_process_hang",
        "kernel/sched/core.c:perf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:perf_trace_sched_kthread_stop"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:migration_init",
        "kernel/sched/core.c:migrate_task_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:migrate_swap",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:perf_trace_sched_pi_setprio",
        "kernel/sched/core.c:perf_trace_sched_stat_runtime",
        "kernel/sched/core.c:perf_trace_sched_stat_template",
        "kernel/sched/core.c:perf_trace_sched_process_exec",
        "kernel/sched/core.c:perf_trace_sched_process_fork",
        "kernel/sched/core.c:perf_trace_sched_process_wait",
        "kernel/sched/core.c:perf_trace_sched_process_template",
        "kernel/sched/core.c:perf_trace_sched_migrate_task",
        "kernel/sched/core.c:perf_trace_sched_switch",
        "kernel/sched/core.c:perf_trace_sched_wakeup_template"
      ]
    },
    {
      "addr": 18446603336490936704,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_load_nohz_stop",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490939420,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_idle_ticks",
        "kernel/sched/cputime.c:account_idle_ticks",
        "kernel/sched/cputime.c:account_idle_ticks",
        "kernel/sched/cputime.c:account_process_tick",
        "kernel/sched/cputime.c:account_process_tick",
        "kernel/sched/cputime.c:account_process_tick",
        "kernel/sched/cputime.c:account_idle_time",
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490941484,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:sched_idle_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490965836,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:attach_entity_load_avg"
      ],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:update_curr"
      ]
    },
    {
      "addr": 18446603336491014336,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rto_push_irq_work_func",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/rt.c:sched_rt_period_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491017472,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:find_later_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491068996,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 0,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491092384,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/cpuacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:cpuacct_account_field",
        "kernel/sched/cpuacct.c:cpuacct_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491092676,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq.c:cpufreq_this_cpu_can_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491093484,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_fast_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491098804,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:__arm64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/sched/membarrier.c:membarrier_exec_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491099272,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup"
      ]
    },
    {
      "addr": 18446603336491104356,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491115604,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:__percpu_up_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491116376,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/locking/osq_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_lock",
        "kernel/locking/osq_lock.c:osq_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491116856,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491131012,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/power/qos.c:pm_qos_work_fn",
        "kernel/power/qos.c:pm_qos_update_flags",
        "kernel/power/qos.c:pm_qos_update_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491138900,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491142984,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 18446603336491163584,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:defer_console_output",
        "kernel/printk/printk.c:defer_console_output",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:perf_trace_console"
      ],
      "caller_func": [
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init",
        "kernel/printk/printk.c:console_init"
      ]
    },
    {
      "addr": 18446603336491167732,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:__printk_safe_exit",
        "kernel/printk/printk_safe.c:__printk_safe_enter",
        "kernel/printk/printk_safe.c:printk_nmi_direct_exit",
        "kernel/printk/printk_safe.c:printk_nmi_direct_enter",
        "kernel/printk/printk_safe.c:printk_nmi_direct_enter",
        "kernel/printk/printk_safe.c:printk_nmi_exit",
        "kernel/printk/printk_safe.c:printk_nmi_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491171816,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:__handle_domain_irq",
        "kernel/irq/irqdesc.c:__handle_domain_irq"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    },
    {
      "addr": 18446603336491173836,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:__handle_irq_event_percpu",
        "kernel/irq/handle.c:__handle_irq_event_percpu",
        "kernel/irq/handle.c:handle_bad_irq",
        "kernel/irq/handle.c:handle_bad_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491176508,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491192548,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:irq_wait_for_poll",
        "kernel/irq/spurious.c:irq_wait_for_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491199696,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_fasteoi_mask_irq",
        "kernel/irq/chip.c:handle_fasteoi_mask_irq",
        "kernel/irq/chip.c:handle_fasteoi_ack_irq",
        "kernel/irq/chip.c:handle_fasteoi_ack_irq",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_irq",
        "kernel/irq/chip.c:handle_percpu_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq",
        "kernel/irq/chip.c:handle_simple_irq",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:handle_nested_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491230116,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491239024,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:perf_trace_rcu_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491250260,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:__srcu_read_unlock",
        "kernel/rcu/srcutree.c:__srcu_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491278544,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_needs_cpu",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_report_dead",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread_should_run",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:__note_gp_changes",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_nmi_enter",
        "kernel/rcu/tree.c:rcu_idle_exit",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_is_cpu_rrupt_from_idle",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_enter"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ]
    },
    {
      "addr": 18446603336491290332,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491298636,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/swiotlb.c:swiotlb_map",
        "kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491307876,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/profile.c:profile_tick",
        "kernel/profile.c:__profile_flip_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491336344,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:run_local_timers",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:timer_clear_idle",
        "kernel/time/timer.c:get_next_timer_interrupt",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:call_timer_fn",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:detach_if_pending",
        "kernel/time/timer.c:enqueue_timer",
        "kernel/time/timer.c:round_jiffies_up_relative",
        "kernel/time/timer.c:round_jiffies_up",
        "kernel/time/timer.c:round_jiffies_relative",
        "kernel/time/timer.c:round_jiffies",
        "kernel/time/timer.c:perf_trace_tick_stop",
        "kernel/time/timer.c:perf_trace_itimer_expire",
        "kernel/time/timer.c:perf_trace_itimer_state",
        "kernel/time/timer.c:perf_trace_hrtimer_class",
        "kernel/time/timer.c:perf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:perf_trace_hrtimer_start",
        "kernel/time/timer.c:perf_trace_hrtimer_init",
        "kernel/time/timer.c:perf_trace_timer_expire_entry",
        "kernel/time/timer.c:perf_trace_timer_start",
        "kernel/time/timer.c:perf_trace_timer_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491345828,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_init_sleeper",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_init",
        "kernel/time/hrtimer.c:__hrtimer_init",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:enqueue_hrtimer",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_init"
      ]
    },
    {
      "addr": 18446603336491374300,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:perf_trace_alarm_class",
        "kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491390456,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491401108,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 18446603336491404468,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:clockevents_register_device",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491410152,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_resume_local",
        "kernel/time/tick-common.c:tick_suspend_local",
        "kernel/time/tick-common.c:tick_handover_do_timer",
        "kernel/time/tick-common.c:tick_broadcast_oneshot_control",
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_install_replacement",
        "kernel/time/tick-common.c:tick_handle_periodic",
        "kernel/time/tick-common.c:tick_periodic",
        "kernel/time/tick-common.c:tick_is_oneshot_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491410844,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_check_broadcast_expired",
        "kernel/time/tick-broadcast.c:tick_resume_check_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-broadcast.c:tick_receive_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491419712,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-oneshot.c:tick_oneshot_mode_active",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491425372,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_oneshot_notify",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls",
        "kernel/time/tick-sched.c:tick_nohz_get_sleep_length",
        "kernel/time/tick-sched.c:tick_nohz_get_next_hrtimer",
        "kernel/time/tick-sched.c:tick_nohz_idle_got_tick",
        "kernel/time/tick-sched.c:tick_nohz_irq_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_retain_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_next_event",
        "kernel/time/tick-sched.c:tick_nohz_stop_idle",
        "kernel/time/tick-sched.c:tick_nohz_tick_stopped",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491453640,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:wake_up_all_idle_cpus",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_any",
        "kernel/smp.c:smp_call_function_single",
        "kernel/smp.c:smp_call_function_single",
        "kernel/smp.c:flush_smp_call_function_queue",
        "kernel/smp.c:flush_smp_call_function_queue",
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": [
        "kernel/smp.c:flush_smp_call_function_queue",
        "kernel/smp.c:call_function_init"
      ]
    },
    {
      "addr": 18446603336491488876,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module",
        "kernel/module.c:try_module_get",
        "kernel/module.c:perf_trace_module_request",
        "kernel/module.c:perf_trace_module_refcnt",
        "kernel/module.c:perf_trace_module_free",
        "kernel/module.c:perf_trace_module_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491506128,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491534352,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_event",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    },
    {
      "addr": 18446603336491572560,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/cgroup/rstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491583664,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491588508,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491591556,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491596724,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge",
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491616892,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491633852,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_machine_from_inactive_cpu",
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": [
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    },
    {
      "addr": 18446603336491689888,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:aggr_fault_handler",
        "kernel/kprobes.c:aggr_post_handler",
        "kernel/kprobes.c:aggr_post_handler",
        "kernel/kprobes.c:aggr_pre_handler",
        "kernel/kprobes.c:aggr_pre_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491706796,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_handle_exception",
        "kernel/debug/debug_core.c:kgdb_roundup_cpus",
        "kernel/debug/debug_core.c:kgdb_call_nmi_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491714912,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/debug/gdbstub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491716092,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491733256,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_cpu",
        "kernel/debug/kdb/kdb_main.c:kdb_go",
        "kernel/debug/kdb/kdb_main.c:kdb_print_state",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491744764,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491757532,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491759228,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:softlockup_start_fn",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:softlockup_fn",
        "kernel/watchdog.c:softlockup_fn",
        "kernel/watchdog.c:is_hardlockup",
        "kernel/watchdog.c:touch_softlockup_watchdog_sync",
        "kernel/watchdog.c:touch_softlockup_watchdog_sync",
        "kernel/watchdog.c:touch_softlockup_watchdog",
        "kernel/watchdog.c:__touch_watchdog"
      ],
      "caller_func": [
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn"
      ]
    },
    {
      "addr": 18446603336491766440,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491773084,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_late_setup_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491784904,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:prepare_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491790256,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock_global"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491797944,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:ftrace_pid_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491845120,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_nest_end",
        "kernel/trace/ring_buffer.c:ring_buffer_nest_start",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491867992,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:put_trace_buf",
        "kernel/trace/trace.c:get_trace_buf",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace.c:disable_trace_buffered_event",
        "kernel/trace/trace.c:enable_trace_buffered_event",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    },
    {
      "addr": 18446603336491925796,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call",
        "kernel/trace/trace_functions.c:function_trace_call",
        "kernel/trace/trace_functions.c:function_trace_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491927152,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491932896,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:trace_hwlat_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491934432,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_stack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_stack.c:t_stop",
        "kernel/trace/trace_stack.c:t_start",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_stack.c:stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491938732,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491954396,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:__trace_note_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491969880,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491981180,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491985988,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_ftrace_event_register",
        "kernel/trace/trace_event_perf.c:perf_ftrace_function_call",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_alloc",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_alloc",
        "kernel/trace/trace_event_perf.c:perf_trace_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491987284,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:filter_pred_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492037844,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:hist_field_cpu",
        "kernel/trace/trace_events_hist.c:action_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492041864,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:put_bpf_raw_tp_regs",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492062724,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:kretprobe_dispatcher",
        "kernel/trace/trace_kprobe.c:kprobe_dispatcher",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492073412,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/power-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:perf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:perf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:perf_trace_power_domain",
        "kernel/trace/power-traces.c:perf_trace_clock",
        "kernel/trace/power-traces.c:perf_trace_wakeup_source",
        "kernel/trace/power-traces.c:perf_trace_suspend_resume",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits",
        "kernel/trace/power-traces.c:perf_trace_pstate_sample",
        "kernel/trace/power-traces.c:perf_trace_powernv_throttle",
        "kernel/trace/power-traces.c:perf_trace_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492076212,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/rpm-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/rpm-traces.c:perf_trace_rpm_return_int",
        "kernel/trace/rpm-traces.c:perf_trace_rpm_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492096464,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/trace/trace_uprobe.c:uprobe_buffer_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492102456,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq_work.c:irq_work_tick",
        "kernel/irq_work.c:irq_work_tick",
        "kernel/irq_work.c:irq_work_run",
        "kernel/irq_work.c:irq_work_run",
        "kernel/irq_work.c:irq_work_needs_cpu",
        "kernel/irq_work.c:irq_work_queue_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492108844,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:perf_trace_mem_return_failed",
        "kernel/bpf/core.c:perf_trace_mem_connect",
        "kernel/bpf/core.c:perf_trace_mem_disconnect",
        "kernel/bpf/core.c:perf_trace_xdp_devmap_xmit",
        "kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:perf_trace_xdp_redirect_template",
        "kernel/bpf/core.c:perf_trace_xdp_bulk_tx",
        "kernel/bpf/core.c:perf_trace_xdp_exception",
        "kernel/bpf/core.c:trace_event_raw_event_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:trace_event_raw_event_xdp_cpumap_kthread",
        "kernel/bpf/core.c:bpf_user_rnd_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492142940,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492214564,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_get_local_storage",
        "kernel/bpf/helpers.c:bpf_get_local_storage",
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:bpf_spin_unlock",
        "kernel/bpf/helpers.c:bpf_spin_lock",
        "kernel/bpf/helpers.c:bpf_get_numa_node_id",
        "kernel/bpf/helpers.c:bpf_get_smp_processor_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492223236,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_elem_free_rcu",
        "kernel/bpf/hashtab.c:htab_elem_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492234968,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492237052,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop",
        "kernel/bpf/percpu_freelist.c:__pcpu_freelist_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492238828,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/bpf_lru_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free",
        "kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492281660,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush",
        "kernel/bpf/devmap.c:bq_xmit_all",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492288820,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492291468,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:__xsk_map_flush",
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492296488,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "kernel/bpf/offload.c:bpf_prog_offload_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492300952,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492312032,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492370824,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:___perf_sw_event",
        "kernel/events/core.c:perf_swevent_put_recursion_context",
        "kernel/events/core.c:perf_swevent_get_recursion_context",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:__perf_pmu_output_stop",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_pending_event",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:perf_sched_cb_inc",
        "kernel/events/core.c:perf_sched_cb_inc",
        "kernel/events/core.c:perf_sched_cb_inc",
        "kernel/events/core.c:perf_sched_cb_dec",
        "kernel/events/core.c:perf_sched_cb_dec",
        "kernel/events/core.c:__perf_event_stop",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:perf_event_disable_inatomic",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/core.c:event_function"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_del_event",
        "kernel/events/core.c:list_add_event"
      ]
    },
    {
      "addr": 18446603336492392616,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492398664,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492414036,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492437932,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:perf_trace_rseq_ip_fixup",
        "kernel/rseq.c:perf_trace_rseq_update",
        "kernel/rseq.c:perf_trace_rseq_update",
        "kernel/rseq.c:trace_event_raw_event_rseq_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492459808,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:perf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:perf_trace_filemap_set_wb_err",
        "mm/filemap.c:perf_trace_mm_filemap_op_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492481640,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:perf_trace_compact_retry",
        "mm/oom_kill.c:perf_trace_skip_task_reaping",
        "mm/oom_kill.c:perf_trace_finish_task_reaping",
        "mm/oom_kill.c:perf_trace_start_task_reaping",
        "mm/oom_kill.c:perf_trace_wake_reaper",
        "mm/oom_kill.c:perf_trace_mark_victim",
        "mm/oom_kill.c:perf_trace_reclaim_retry_zone",
        "mm/oom_kill.c:perf_trace_oom_score_adj_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492507520,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:domain_dirty_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492520000,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_drain",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:pagevec_move_tail",
        "mm/swap.c:perf_trace_mm_lru_activate",
        "mm/swap.c:perf_trace_mm_lru_insertion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492574448,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:perf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate",
        "mm/vmscan.c:perf_trace_mm_shrink_slab_end",
        "mm/vmscan.c:perf_trace_mm_shrink_slab_start",
        "mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd",
        "mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake",
        "mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492596004,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492633568,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:quiet_vmstat",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:__inc_numa_state",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:refresh_cpu_vm_stats",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:dec_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_page_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:inc_node_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:mod_node_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:dec_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:inc_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:vm_events_fold_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492636544,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:bdi_register_va",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492646292,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492658372,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/percpu.c:perf_trace_percpu_destroy_chunk",
        "mm/percpu.c:perf_trace_percpu_create_chunk",
        "mm/percpu.c:perf_trace_percpu_alloc_percpu_fail",
        "mm/percpu.c:perf_trace_percpu_free_percpu",
        "mm/percpu.c:perf_trace_percpu_alloc_percpu",
        "mm/percpu.c:pcpu_setup_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492673216,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order_trace",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:perf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:perf_trace_mm_page",
        "mm/slab_common.c:perf_trace_mm_page_alloc",
        "mm/slab_common.c:perf_trace_mm_page_free_batched",
        "mm/slab_common.c:perf_trace_mm_page_free",
        "mm/slab_common.c:perf_trace_kmem_free",
        "mm/slab_common.c:perf_trace_kmem_alloc_node",
        "mm/slab_common.c:perf_trace_kmem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492700204,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_suitable",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:compaction_deferred",
        "mm/compaction.c:defer_compaction",
        "mm/compaction.c:perf_trace_kcompactd_wake_template",
        "mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep",
        "mm/compaction.c:perf_trace_mm_compaction_defer_template",
        "mm/compaction.c:perf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:perf_trace_mm_compaction_end",
        "mm/compaction.c:perf_trace_mm_compaction_begin",
        "mm/compaction.c:perf_trace_mm_compaction_migratepages",
        "mm/compaction.c:perf_trace_mm_compaction_isolate_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492721904,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492753700,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492768012,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492798320,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492849176,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492858404,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:nr_free_zone_pages",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page_commit",
        "mm/page_alloc.c:free_unref_page_commit",
        "mm/page_alloc.c:drain_local_pages",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": [
        "mm/page_alloc.c:show_free_areas"
      ]
    },
    {
      "addr": 18446603336492911132,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492917996,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492931308,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_try_ssd_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492949048,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:free_swap_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492956012,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492971268,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493020964,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:mpol_misplaced",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:init_nodemask_of_mempolicy",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:change_prot_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503921124,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493047752,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493090356,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:flush_cpu_slab",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:bootstrap",
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:set_track"
      ]
    },
    {
      "addr": 18446603336493096288,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:restore_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback",
        "mm/memory_hotplug.c:set_online_page_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493116916,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:perf_trace_mm_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493147588,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_huge_page",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493165924,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:khugepaged_alloc_page",
        "mm/khugepaged.c:khugepaged_alloc_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin",
        "mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate",
        "mm/khugepaged.c:perf_trace_mm_collapse_huge_page",
        "mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493200452,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:refill_stock",
        "mm/memcontrol.c:drain_local_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:percpu_ref_put_many",
        "mm/memcontrol.c:percpu_ref_tryget_live"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_flush_foreign",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    },
    {
      "addr": 18446603336493225736,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493238516,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_work_func",
        "mm/memory-failure.c:memory_failure_queue",
        "mm/memory-failure.c:memory_failure_queue",
        "mm/memory-failure.c:action_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493245000,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:perf_trace_test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493256880,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493265688,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_release",
        "mm/cma.c:cma_alloc",
        "mm/cma.c:perf_trace_cma_release",
        "mm/cma.c:perf_trace_cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493267556,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493269584,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493283468,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493298012,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_sys_open",
        "fs/open.c:perf_trace_open_exec",
        "fs/open.c:perf_trace_do_sys_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493327024,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493363220,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:__set_task_comm",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/exec.c:do_open_execat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493459220,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_instantiate",
        "fs/dcache.c:__d_alloc",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_lru_shrink_move",
        "fs/dcache.c:d_shrink_add",
        "fs/dcache.c:d_shrink_del",
        "fs/dcache.c:d_lru_del",
        "fs/dcache.c:d_lru_del",
        "fs/dcache.c:d_lru_add",
        "fs/dcache.c:d_lru_add",
        "fs/dcache.c:dentry_unlink_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493485192,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:inode_lru_list_add",
        "fs/inode.c:__destroy_inode",
        "fs/inode.c:__destroy_inode",
        "fs/inode.c:inode_init_always"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493532860,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__arm64_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:mnt_set_mountpoint",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_clone_write",
        "fs/namespace.c:__mnt_want_write",
        "fs/namespace.c:__mnt_want_write",
        "fs/namespace.c:alloc_vfsmnt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493599460,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:__mark_inode_dirty",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn",
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
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:perf_trace_writeback_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_global_dirty_state",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_pages_written",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493662276,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:buffer_exit_cpu_dead",
        "fs/buffer.c:alloc_buffer_head",
        "fs/buffer.c:invalidate_bh_lru",
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493700088,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493731648,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493785412,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_signal",
        "fs/eventfd.c:eventfd_signal",
        "fs/eventfd.c:eventfd_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493810964,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__arm64_sys_io_cancel",
        "fs/aio.c:__arm64_compat_sys_io_submit",
        "fs/aio.c:__arm64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__arm64_sys_io_destroy",
        "fs/aio.c:__arm64_compat_sys_io_setup",
        "fs/aio.c:__arm64_sys_io_setup",
        "fs/aio.c:lookup_ioctx",
        "fs/aio.c:__get_reqs_available",
        "fs/aio.c:put_reqs_available",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493849244,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_enter",
        "fs/io_uring.c:__arm64_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493863544,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:perf_trace_dax_writeback_one",
        "fs/dax.c:perf_trace_dax_writeback_range_class",
        "fs/dax.c:perf_trace_dax_insert_mapping",
        "fs/dax.c:perf_trace_dax_pte_fault_class",
        "fs/dax.c:perf_trace_dax_pmd_insert_mapping_class",
        "fs/dax.c:perf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:perf_trace_dax_pmd_fault_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493930792,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:locks_remove_posix",
        "fs/locks.c:fcntl_setlk",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:leases_conflict",
        "fs/locks.c:time_out_leases",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:locks_insert_global_locks",
        "fs/locks.c:locks_insert_global_locks",
        "fs/locks.c:locks_get_lock_context",
        "fs/locks.c:perf_trace_leases_conflict",
        "fs/locks.c:perf_trace_generic_add_lease",
        "fs/locks.c:perf_trace_filelock_lease",
        "fs/locks.c:perf_trace_filelock_lock",
        "fs/locks.c:perf_trace_locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493994356,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/drop_caches.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494086104,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:__set_oom_adj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494222988,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494234584,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 18446603336494270204,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:get_implied_cluster_alloc",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
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
      "addr": 18446603336494285772,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 18446603336494294224,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 18446603336494295472,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494305436,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 18446603336494315720,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_ind_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494368528,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/inode.c:__ext4_journalled_invalidatepage",
        "fs/ext4/inode.c:ext4_alloc_da_blocks",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_dax_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_da_release_space",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446603336494402576,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_getfsmap_format"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494432804,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_initialize_context",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494490732,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494580116,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_nfs_commit_metadata",
        "fs/ext4/super.c:ext4_drop_inode",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error",
        "fs/ext4/super.c:perf_trace_ext4_error",
        "fs/ext4/super.c:perf_trace_ext4_shutdown",
        "fs/ext4/super.c:perf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:perf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:perf_trace_ext4_insert_range",
        "fs/ext4/super.c:perf_trace_ext4_collapse_range",
        "fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit",
        "fs/ext4/super.c:perf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter",
        "fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter",
        "fs/ext4/super.c:perf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:perf_trace_ext4__es_extent",
        "fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:perf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:perf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:perf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:perf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:perf_trace_ext4_find_delalloc_range",
        "fs/ext4/super.c:perf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:perf_trace_ext4__trim",
        "fs/ext4/super.c:perf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:perf_trace_ext4_journal_start",
        "fs/ext4/super.c:perf_trace_ext4_load_inode",
        "fs/ext4/super.c:perf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:perf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:perf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:perf_trace_ext4__truncate",
        "fs/ext4/super.c:perf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:perf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:perf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:perf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:perf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:perf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:perf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:perf_trace_ext4_da_release_space",
        "fs/ext4/super.c:perf_trace_ext4_da_reserve_space",
        "fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:perf_trace_ext4_forget",
        "fs/ext4/super.c:perf_trace_ext4__mballoc",
        "fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc",
        "fs/ext4/super.c:perf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks",
        "fs/ext4/super.c:perf_trace_ext4_sync_fs",
        "fs/ext4/super.c:perf_trace_ext4_sync_file_exit",
        "fs/ext4/super.c:perf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:perf_trace_ext4_free_blocks",
        "fs/ext4/super.c:perf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:perf_trace_ext4_request_blocks",
        "fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:perf_trace_ext4_discard_preallocations",
        "fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:perf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:perf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:perf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:perf_trace_ext4__page_op",
        "fs/ext4/super.c:perf_trace_ext4_writepages_result",
        "fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:perf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:perf_trace_ext4_writepages",
        "fs/ext4/super.c:perf_trace_ext4__write_end",
        "fs/ext4/super.c:perf_trace_ext4__write_begin",
        "fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty",
        "fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata",
        "fs/ext4/super.c:perf_trace_ext4_drop_inode",
        "fs/ext4/super.c:perf_trace_ext4_evict_inode",
        "fs/ext4/super.c:perf_trace_ext4_allocate_inode",
        "fs/ext4/super.c:perf_trace_ext4_request_inode",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494655036,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_start_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494675620,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    },
    {
      "addr": 18446603336494682192,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 18446603336494706680,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:perf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail",
        "fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:perf_trace_jbd2_run_stats",
        "fs/jbd2/journal.c:perf_trace_jbd2_handle_stats",
        "fs/jbd2/journal.c:perf_trace_jbd2_handle_extend",
        "fs/jbd2/journal.c:perf_trace_jbd2_handle_start",
        "fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data",
        "fs/jbd2/journal.c:perf_trace_jbd2_end_commit",
        "fs/jbd2/journal.c:perf_trace_jbd2_commit",
        "fs/jbd2/journal.c:perf_trace_jbd2_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495164612,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_node_kill",
        "security/selinux/avc.c:avc_node_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495235216,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "security/selinux/netif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/netif.c:sel_netif_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495363004,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "security/lsm_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/lsm_audit.c:dump_common_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495457640,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495482292,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:profile_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495530156,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_file_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495557068,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495681872,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "crypto/scompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495775088,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/bio.c:update_io_ticks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495807636,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:blk_queue_enter",
        "block/blk-core.c:blk_queue_enter",
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_unplug",
        "block/blk-core.c:perf_trace_block_plug",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:perf_trace_block_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495834940,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_queue_split"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495841624,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "block/blk-softirq.c:blk_done_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495867200,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_start_request",
        "block/blk-mq.c:blk_mq_complete_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495875916,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495878512,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495886600,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_request_inserted",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495901644,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_dec_in_flight",
        "block/genhd.c:part_dec_in_flight",
        "block/genhd.c:part_inc_in_flight",
        "block/genhd.c:part_inc_in_flight"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495982712,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495995368,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued",
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496021784,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj",
        "block/blk-iocost.c:perf_trace_iocg_inuse_update",
        "block/blk-iocost.c:perf_trace_iocost_iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496062672,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:wb_timer_fn",
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496095512,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_bytes",
        "lib/random32.c:prandom_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496141912,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496311044,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_add_batch",
        "lib/percpu_counter.c:percpu_counter_add_batch",
        "lib/percpu_counter.c:percpu_counter_add_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496348308,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496357836,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "lib/sbitmap.c:__sbitmap_queue_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490161852,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/irqchip/irq-bcm2836.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_unmask_pmu_irq",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_mask_pmu_irq",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_unmask_timer_irq",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_mask_timer_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496366988,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic.c:gic_cpu_restore",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496378612,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_set_affinity",
        "drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init",
        "drivers/irqchip/irq-gic-v3.c:gic_populate_rdist",
        "drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist",
        "drivers/irqchip/irq-gic-v3.c:gic_handle_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_handle_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_set_type",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_set_prio",
        "drivers/irqchip/irq-gic-v3.c:gic_poke_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_peek_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_redist_wait_for_rwp"
      ],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist",
        "drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist",
        "drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist"
      ]
    },
    {
      "addr": 18446603336496401088,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_restore_enable",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis"
      ],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis"
      ]
    },
    {
      "addr": 18446603336496404996,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/irqchip/irq-partition-percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-partition-percpu.c:partition_handle_irq",
        "drivers/irqchip/irq-partition-percpu.c:partition_irq_get_irqchip_state",
        "drivers/irqchip/irq-partition-percpu.c:partition_irq_set_irqchip_state",
        "drivers/irqchip/irq-partition-percpu.c:partition_irq_unmask",
        "drivers/irqchip/irq-partition-percpu.c:partition_irq_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496411024,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496429832,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/irqchip/qcom-irq-combiner.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496462720,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/bus/fsl-mc/dprc-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/fsl-mc/dprc-driver.c:dprc_irq0_handler_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496725812,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:perf_trace_gpio_value",
        "drivers/gpio/gpiolib.c:perf_trace_gpio_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496779272,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/gpio/gpio-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_mask",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496783440,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/gpio/gpio-mxc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496993356,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497436584,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497638380,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_lpi_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497758344,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
        "drivers/clk/clk.c:clk_core_unprepare",
        "drivers/clk/clk.c:perf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:perf_trace_clk_phase",
        "drivers/clk/clk.c:perf_trace_clk_parent",
        "drivers/clk/clk.c:perf_trace_clk_rate",
        "drivers/clk/clk.c:perf_trace_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498003832,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_find_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511189452,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/dma/ipu/ipu_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498092628,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/soc/fsl/qbman/bman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman.c:bman_acquire",
        "drivers/soc/fsl/qbman/bman.c:bman_release",
        "drivers/soc/fsl/qbman/bman.c:bman_release",
        "drivers/soc/fsl/qbman/bman.c:bm_shutdown_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498114204,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq",
        "drivers/soc/fsl/qbman/qman.c:qman_delete_cgr_safe",
        "drivers/soc/fsl/qbman/qman.c:qman_delete_cgr",
        "drivers/soc/fsl/qbman/qman.c:qman_create_cgr",
        "drivers/soc/fsl/qbman/qman.c:qman_enqueue",
        "drivers/soc/fsl/qbman/qman.c:set_vdqcr",
        "drivers/soc/fsl/qbman/qman.c:qman_query_fq_np",
        "drivers/soc/fsl/qbman/qman.c:qman_query_fq",
        "drivers/soc/fsl/qbman/qman.c:qman_oos_fq",
        "drivers/soc/fsl/qbman/qman.c:qman_retire_fq",
        "drivers/soc/fsl/qbman/qman.c:qman_schedule_fq",
        "drivers/soc/fsl/qbman/qman.c:qman_init_fq",
        "drivers/soc/fsl/qbman/qman.c:qman_affine_channel",
        "drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal",
        "drivers/soc/fsl/qbman/qman.c:portal_isr",
        "drivers/soc/fsl/qbman/qman.c:portal_isr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498134316,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/soc/qcom/rpmh-rsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write",
        "drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done",
        "drivers/soc/qcom/rpmh-rsc.c:perf_trace_rpmh_send_msg",
        "drivers/soc/qcom/rpmh-rsc.c:perf_trace_rpmh_tx_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498196780,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498214704,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/xen/preempt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/preempt.c:xen_maybe_preempt_hcall",
        "drivers/xen/preempt.c:xen_maybe_preempt_hcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498215780,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/time.c:xen_get_runstate_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498226236,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall",
        "drivers/xen/events/events_base.c:__xen_evtchn_do_upcall",
        "drivers/xen/events/events_base.c:__xen_evtchn_do_upcall",
        "drivers/xen/events/events_base.c:__xen_evtchn_do_upcall",
        "drivers/xen/events/events_base.c:__xen_evtchn_do_upcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498229572,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:xen_debug_interrupt",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events",
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511199864,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498273632,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498303948,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_set_voltage",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:perf_trace_regulator_value",
        "drivers/regulator/core.c:perf_trace_regulator_range",
        "drivers/regulator/core.c:perf_trace_regulator_basic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498430100,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498453604,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498741940,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:urandom_read",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_xfer_secondary_pool",
        "drivers/char/random.c:add_disk_randomness",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_backtrack_protect",
        "drivers/char/random.c:extract_crng",
        "drivers/char/random.c:credit_entropy_bits",
        "drivers/char/random.c:mix_pool_bytes",
        "drivers/char/random.c:__mix_pool_bytes",
        "drivers/char/random.c:perf_trace_urandom_read",
        "drivers/char/random.c:perf_trace_random_read",
        "drivers/char/random.c:perf_trace_random__extract_entropy",
        "drivers/char/random.c:perf_trace_random__get_random_bytes",
        "drivers/char/random.c:perf_trace_xfer_secondary_pool",
        "drivers/char/random.c:perf_trace_add_disk_randomness",
        "drivers/char/random.c:perf_trace_add_input_randomness",
        "drivers/char/random.c:perf_trace_debit_entropy",
        "drivers/char/random.c:perf_trace_push_to_pool",
        "drivers/char/random.c:perf_trace_credit_entropy_bits",
        "drivers/char/random.c:perf_trace_random__mix_pool_bytes",
        "drivers/char/random.c:perf_trace_add_device_randomness"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498828656,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_aux_detach_device",
        "drivers/iommu/iommu.c:iommu_aux_attach_device",
        "drivers/iommu/iommu.c:report_iommu_fault",
        "drivers/iommu/iommu.c:__iommu_unmap",
        "drivers/iommu/iommu.c:iommu_map",
        "drivers/iommu/iommu.c:__iommu_attach_device",
        "drivers/iommu/iommu.c:iommu_group_remove_device",
        "drivers/iommu/iommu.c:iommu_group_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498841096,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/iommu/iommu-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_unmap",
        "drivers/iommu/iommu-traces.c:perf_trace_map",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498849172,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498852908,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498863948,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:iova_rcache_get",
        "drivers/iommu/iova.c:iova_rcache_insert",
        "drivers/iommu/iova.c:queue_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498932052,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/connector/cn_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/connector/cn_proc.c:proc_exit_connector",
        "drivers/connector/cn_proc.c:proc_exit_connector",
        "drivers/connector/cn_proc.c:proc_coredump_connector",
        "drivers/connector/cn_proc.c:proc_coredump_connector",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/connector/cn_proc.c:proc_ptrace_connector",
        "drivers/connector/cn_proc.c:proc_ptrace_connector",
        "drivers/connector/cn_proc.c:proc_sid_connector",
        "drivers/connector/cn_proc.c:proc_sid_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_exec_connector",
        "drivers/connector/cn_proc.c:proc_exec_connector",
        "drivers/connector/cn_proc.c:proc_fork_connector",
        "drivers/connector/cn_proc.c:proc_fork_connector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498985136,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 18446603336499042712,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 18446603336499053756,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446603336499080792,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499084080,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499148140,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
        "drivers/base/regmap/regmap.c:_regmap_raw_write_impl",
        "drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_async",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_bool",
        "drivers/base/regmap/regmap.c:perf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499167900,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/base/regmap/regcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache.c:regcache_cache_bypass",
        "drivers/base/regmap/regcache.c:regcache_cache_only",
        "drivers/base/regmap/regcache.c:regcache_drop_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499220268,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499427892,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:generic_nvdimm_flush",
        "drivers/nvdimm/region_devs.c:generic_nvdimm_flush",
        "drivers/nvdimm/region_devs.c:nd_region_release_lane",
        "drivers/nvdimm/region_devs.c:nd_region_acquire_lane"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499487816,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_init",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal_locked",
        "drivers/dma-buf/dma-fence.c:perf_trace_dma_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499508304,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499520568,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/scsi/scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499542604,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_times_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499565268,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_done",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499701188,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc",
        "drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy",
        "drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template",
        "drivers/ata/libata-core.c:perf_trace_ata_qc_issue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499765640,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499884936,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_async",
        "drivers/spi/spi.c:spi_finalize_current_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:perf_trace_spi_transfer",
        "drivers/spi/spi.c:perf_trace_spi_message_done",
        "drivers/spi/spi.c:perf_trace_spi_message",
        "drivers/spi/spi.c:perf_trace_spi_controller"
      ],
      "caller_func": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    },
    {
      "addr": 18446603336499921448,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499952288,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_write",
        "drivers/net/phy/mdio_bus.c:__mdiobus_read",
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499973428,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_show_fdinfo",
        "drivers/net/tun.c:tun_chr_show_fdinfo",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_peek_len",
        "drivers/net/tun.c:tun_peek_len",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_chr_read_iter",
        "drivers/net/tun.c:tun_chr_read_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_chr_write_iter",
        "drivers/net/tun.c:tun_chr_write_iter",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_chr_poll",
        "drivers/net/tun.c:tun_chr_poll",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_flow_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500004488,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500029236,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_close",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500130256,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500152920,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500603408,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_configure_endpoint",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_setup_device"
      ]
    },
    {
      "addr": 18446603336500614312,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
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
      "addr": 18446603336500629472,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:inc_enq",
        "drivers/usb/host/xhci-ring.c:inc_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500667904,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500682384,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500687424,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/usb/host/xhci-dbgcap.c:dbc_free_request",
        "drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500710620,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500813992,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:rtc_set_offset",
        "drivers/rtc/interface.c:rtc_read_offset",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/rtc/interface.c:rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/interface.c:perf_trace_rtc_timer_class",
        "drivers/rtc/interface.c:perf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:perf_trace_rtc_irq_set_state",
        "drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq",
        "drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500841884,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:perf_trace_i2c_result",
        "drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply",
        "drivers/i2c/i2c-core-base.c:perf_trace_i2c_read",
        "drivers/i2c/i2c-core-base.c:perf_trace_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500854944,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500947532,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/power/reset/sc27xx-poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/reset/sc27xx-poweroff.c:sc27xx_poweroff_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500973316,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/hwmon/hwmon.c:hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:hwmon_attr_show",
        "drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500987448,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip",
        "drivers/thermal/thermal_core.c:perf_trace_cdev_update",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_temperature"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501004364,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_helpers.c:thermal_cdev_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501010480,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/thermal/fair_share.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/fair_share.c:fair_share_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501012060,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/thermal/step_wise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/step_wise.c:thermal_zone_trip_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501016544,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power",
        "drivers/thermal/power_allocator.c:allocate_power",
        "drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid",
        "drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501018524,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/thermal/cpu_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/cpu_cooling.c:cpufreq_power2state",
        "drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501022728,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state",
        "drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501078668,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501163448,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501217104,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:__dm_stat_clear",
        "drivers/md/dm-stats.c:__dm_stat_clear",
        "drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501226220,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/md/dm-rq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-rq.c:map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501232616,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501251252,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/ghes_edac.c:ghes_edac_report_mem_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501301140,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501312000,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501319004,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_irq_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501325656,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501327612,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_get_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501334688,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/cpuidle/governors/ladder.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501335332,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_reflect",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501339932,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/cpuidle/cpuidle-psci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle-psci.c:psci_enter_idle_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501347372,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:mmc_cqe_request_done",
        "drivers/mmc/core/core.c:mmc_cqe_start_req",
        "drivers/mmc/core/core.c:__mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/mmc/core/core.c:perf_trace_mmc_request_done",
        "drivers/mmc/core/core.c:perf_trace_mmc_request_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501473752,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501476804,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/firmware/arm_sdei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_sdei.c:_local_event_register"
      ],
      "caller_func": [
        "drivers/firmware/arm_sdei.c:sdei_event_handler",
        "drivers/firmware/arm_sdei.c:_ipi_private_reset",
        "drivers/firmware/arm_sdei.c:sdei_unmask_local_cpu",
        "drivers/firmware/arm_sdei.c:sdei_mask_local_cpu"
      ]
    },
    {
      "addr": 18446603336501563332,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/firmware/efi/arm-runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501590164,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_evtstrm_available",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_check_ool_workaround",
        "drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_stable",
        "drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntpct_stable"
      ],
      "caller_func": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_check_ool_workaround"
      ]
    },
    {
      "addr": 18446603336501660772,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:send_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501664240,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/platform/chrome/cros_ec_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501716472,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501758192,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501770796,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501776988,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu.c:cpu_pm_pmu_notify",
        "drivers/perf/arm_pmu.c:cpu_pm_pmu_notify",
        "drivers/perf/arm_pmu.c:armpmu_filter_match",
        "drivers/perf/arm_pmu.c:armpmu_enable",
        "drivers/perf/arm_pmu.c:armpmu_enable",
        "drivers/perf/arm_pmu.c:armpmu_add",
        "drivers/perf/arm_pmu.c:armpmu_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501779400,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/perf/arm_pmu_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501780068,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/perf/arm_pmu_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501814372,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "drivers/ras/ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/ras.c:log_arm_hw_error",
        "drivers/ras/ras.c:log_non_standard_event",
        "drivers/ras/ras.c:perf_trace_memory_failure_event",
        "drivers/ras/ras.c:perf_trace_aer_event",
        "drivers/ras/ras.c:perf_trace_non_standard_event",
        "drivers/ras/ras.c:perf_trace_arm_event",
        "drivers/ras/ras.c:perf_trace_mc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501866516,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_prot_inuse_add",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501926672,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush",
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501935604,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501966424,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502018232,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:__napi_schedule_irqoff",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_frags",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:flush_backlog",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb_list",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:netif_receive_skb",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:netif_rx_internal",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:netdev_core_pick_tx",
        "net/core/dev.c:dev_pick_tx_cpu_id",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/core/dev.c:dev_getfirstbyhwtype",
        "net/core/dev.c:dev_get_by_index",
        "net/core/dev.c:dev_get_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502070172,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502086012,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_dev_put",
        "net/core/dst.c:dst_dev_put",
        "net/core/dst.c:dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502103256,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_timer_handler",
        "net/core/neighbour.c:neigh_invalidate",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:pneigh_delete",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_lookup_nodev",
        "net/core/neighbour.c:neigh_lookup_nodev",
        "net/core/neighbour.c:neigh_lookup",
        "net/core/neighbour.c:neigh_lookup",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:pneigh_queue_purge",
        "net/core/neighbour.c:neigh_cleanup_and_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502162412,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/utils.c:inet6_pton"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502164020,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_do_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502227692,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:bpf_skb_set_tunnel_opt",
        "net/core/filter.c:bpf_skb_set_tunnel_key",
        "net/core/filter.c:bpf_xdp_redirect_map",
        "net/core/filter.c:bpf_xdp_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_flush_map",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:bpf_get_raw_cpu_id",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502234724,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502243536,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_xa_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502263880,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:netdev_queue_release",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects",
        "net/core/net-sysfs.c:rx_queue_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502267008,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:__page_pool_clean_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502272876,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502282924,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_cleanup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:netpoll_poll_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:netpoll_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502319256,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_neigh__update",
        "net/core/net-traces.c:perf_trace_neigh_update",
        "net/core/net-traces.c:perf_trace_neigh_create",
        "net/core/net-traces.c:perf_trace_page_pool_state_hold",
        "net/core/net-traces.c:perf_trace_page_pool_state_release",
        "net/core/net-traces.c:perf_trace_page_pool_inflight",
        "net/core/net-traces.c:perf_trace_br_fdb_update",
        "net/core/net-traces.c:perf_trace_fdb_delete",
        "net/core/net-traces.c:perf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:perf_trace_br_fdb_add",
        "net/core/net-traces.c:perf_trace_qdisc_dequeue",
        "net/core/net-traces.c:perf_trace_fib_table_lookup",
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:perf_trace_tcp_event_sk_skb",
        "net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:perf_trace_inet_sock_set_state",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:perf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:perf_trace_napi_poll",
        "net/core/net-traces.c:perf_trace_net_dev_rx_exit_template",
        "net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template",
        "net/core/net-traces.c:perf_trace_net_dev_template",
        "net/core/net-traces.c:perf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:perf_trace_net_dev_xmit",
        "net/core/net-traces.c:perf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:perf_trace_consume_skb",
        "net/core/net-traces.c:perf_trace_kfree_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502327604,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_metadata_free",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502332944,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502334148,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/netprio_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netprio_cgroup.c:write_priomap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502342052,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502354476,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_get_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4",
        "net/core/dst_cache.c:dst_cache_get_ip4",
        "net/core/dst_cache.c:dst_cache_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502412984,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_trap_report",
        "net/core/devlink.c:devlink_trap_report",
        "net/core/devlink.c:devlink_health_report",
        "net/core/devlink.c:devlink_health_report",
        "net/core/devlink.c:perf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:perf_trace_devlink_health_recover_aborted",
        "net/core/devlink.c:perf_trace_devlink_health_report",
        "net/core/devlink.c:perf_trace_devlink_hwerr",
        "net/core/devlink.c:perf_trace_devlink_hwmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502414332,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro_cells.c:gro_cells_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502452324,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:pfifo_fast_dequeue",
        "net/sched/sch_generic.c:pfifo_fast_dequeue",
        "net/sched/sch_generic.c:pfifo_fast_dequeue",
        "net/sched/sch_generic.c:__netdev_watchdog_up",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
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
      "addr": 18446603336502462884,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502523616,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502553072,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:perf_trace_bpf_test_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502565712,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502595744,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:rt_flush_dev",
        "net/ipv4/route.c:rt_flush_dev",
        "net/ipv4/route.c:rt_add_uncached_list",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502602636,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502607244,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502608828,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502630156,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_skb",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502644120,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502650384,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502656648,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:tw_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502661480,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502695980,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_push"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502715648,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_syn_flood_action",
        "net/ipv4/tcp_input.c:tcp_syn_flood_action",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_newly_delivered",
        "net/ipv4/tcp_input.c:tcp_newly_delivered",
        "net/ipv4/tcp_input.c:tcp_oow_rate_limited",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_input.c:tcp_check_reno_reordering",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    },
    {
      "addr": 18446603336502759204,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_fragment"
      ]
    },
    {
      "addr": 18446603336502773896,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_syn_ack_timeout",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502788752,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446603336502806000,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502821296,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502822476,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_mark_skb_lost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502829192,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502836556,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502867152,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ]
    },
    {
      "addr": 18446603336502880544,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502890152,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/icmp.c:icmp_out_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502906708,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_init",
        "net/ipv4/devinet.c:in_dev_finish_destroy",
        "net/ipv4/devinet.c:__ip_dev_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502920148,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:inet_sk_state_store",
        "net/ipv4/af_inet.c:inet_sk_set_state",
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/af_inet.c:inet_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502967784,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v6_gw",
        "net/ipv4/fib_semantics.c:fib_nh_common_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502986056,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503003676,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503010732,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503054276,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503075028,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503078776,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_acked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503096712,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:xfrm4_fill_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503109728,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_ifdown",
        "net/xfrm/xfrm_policy.c:xfrm_dst_ifdown",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503146040,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503173104,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503183280,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503189992,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503220376,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503233636,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_send_skb",
        "net/ipv6/ip6_output.c:ip6_send_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit"
      ]
    },
    {
      "addr": 18446603336503254540,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503297004,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503357860,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:fib6_table_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:rt6_probe_deferred",
        "net/ipv6/route.c:rt6_uncached_list_add",
        "net/ipv6/route.c:perf_trace_fib6_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503391924,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503402192,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503417580,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb"
      ]
    },
    {
      "addr": 18446603336503434424,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503446368,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503459424,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503482540,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/reassembly.c:ip6_frag_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503496268,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446603336503502264,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503505624,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    },
    {
      "addr": 18446603336503537112,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2_finish",
        "net/ipv6/ip6mr.c:ip6mr_forward2_finish",
        "net/ipv6/ip6mr.c:ip6mr_forward2_finish",
        "net/ipv6/ip6mr.c:ip6mr_forward2_finish",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503561172,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503562696,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503563968,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503568440,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503576144,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503596992,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503599324,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ],
      "caller_func": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_init"
      ]
    },
    {
      "addr": 18446603336503603008,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf_core.c:in6_dev_finish_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503615576,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503635700,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_direct_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503657364,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_do_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503693212,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503738636,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/switchdev/switchdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/switchdev/switchdev.c:switchdev_deferred_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503771996,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503782236,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503791736,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_clear_dev",
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503806524,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "lib/dump_stack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dump_stack.c:dump_stack_print_info"
      ],
      "caller_func": [
        "lib/dump_stack.c:dump_stack"
      ]
    },
    {
      "addr": 18446603336503846400,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:22",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_preload",
        "lib/radix-tree.c:__radix_tree_preload"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490237368,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336496372112,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490174064,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490184592,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490258768,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490267208,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490269304,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490302096,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490350664,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490639376,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490642624,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490656712,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490793048,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490873320,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490882104,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336490942680,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336491099272,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336491146248,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336491168184,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336491252720,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336491337272,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336491453192,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336491523488,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336491630112,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336491757904,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336491851592,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336492321592,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336492853488,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336493050840,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336493174624,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336493349672,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336494338816,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336494667848,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336496381384,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336499861752,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336500565056,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336501474528,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336501587088,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336502667776,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336502700440,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336502744352,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336502779248,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336502840376,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336503230600,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336503408224,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336503483576,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336503502712,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336503597640,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336503806504,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446603336503841632,
      "name": "__my_cpu_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
  "name": "__my_cpu_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224383324,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:perf_trace_initcall_finish",
        "init/main.c:perf_trace_initcall_start",
        "init/main.c:perf_trace_initcall_level"
      ],
      "caller_func": []
    },
    {
      "addr": 3224418160,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/ptrace.c:perf_trace_sys_exit",
        "arch/arm/kernel/ptrace.c:perf_trace_sys_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3224379912,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/traps.c:handle_fiq_as_nmi",
        "arch/arm/kernel/traps.c:handle_fiq_as_nmi",
        "arch/arm/kernel/traps.c:handle_fiq_as_nmi",
        "arch/arm/kernel/traps.c:handle_fiq_as_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 3224450008,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:perf_trace_ipi_handler",
        "arch/arm/kernel/smp.c:perf_trace_ipi_raise"
      ],
      "caller_func": []
    },
    {
      "addr": 3224455168,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/kernel/smp_twd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp_twd.c:twd_timer_dying_cpu",
        "arch/arm/kernel/smp_twd.c:twd_timer_setup",
        "arch/arm/kernel/smp_twd.c:twd_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 3224457408,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/kernel/machine_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core"
      ],
      "caller_func": []
    },
    {
      "addr": 3224464996,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/kernel/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending",
        "arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending",
        "arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending",
        "arch/arm/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint",
        "arch/arm/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint",
        "arch/arm/kernel/hw_breakpoint.c:arch_install_hw_breakpoint",
        "arch/arm/kernel/hw_breakpoint.c:arch_install_hw_breakpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 3224475020,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/kernel/perf_event_v7.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/perf_event_v7.c:scorpion_pmu_enable_event",
        "arch/arm/kernel/perf_event_v7.c:scorpion_pmu_disable_event",
        "arch/arm/kernel/perf_event_v7.c:krait_pmu_enable_event",
        "arch/arm/kernel/perf_event_v7.c:krait_pmu_disable_event",
        "arch/arm/kernel/perf_event_v7.c:armv7pmu_stop",
        "arch/arm/kernel/perf_event_v7.c:armv7pmu_start",
        "arch/arm/kernel/perf_event_v7.c:armv7pmu_handle_irq",
        "arch/arm/kernel/perf_event_v7.c:armv7pmu_handle_irq",
        "arch/arm/kernel/perf_event_v7.c:armv7pmu_disable_event",
        "arch/arm/kernel/perf_event_v7.c:armv7pmu_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3236558948,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3224509716,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/mm/highmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/highmem.c:kmap_atomic_pfn",
        "arch/arm/mm/highmem.c:__kunmap_atomic",
        "arch/arm/mm/highmem.c:__kunmap_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3224514476,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/mm/proc-v7-bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/proc-v7-bugs.c:cpu_v7_ca15_ibe",
        "arch/arm/mm/proc-v7-bugs.c:cpu_v7_ca8_ibe"
      ],
      "caller_func": []
    },
    {
      "addr": 3224527988,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/common/bL_switcher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/bL_switcher.c:perf_trace_cpu_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 3236563628,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/probes/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/probes/kprobes/core.c:trampoline_handler",
        "arch/arm/probes/kprobes/core.c:trampoline_handler",
        "arch/arm/probes/kprobes/core.c:trampoline_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_fault_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_fault_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_fault_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_fault_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_handler",
        "arch/arm/probes/kprobes/core.c:kprobe_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3224536204,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "arch/arm/probes/kprobes/opt-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/probes/kprobes/opt-arm.c:optimized_callback",
        "arch/arm/probes/kprobes/opt-arm.c:optimized_callback",
        "arch/arm/probes/kprobes/opt-arm.c:optimized_callback",
        "arch/arm/probes/kprobes/opt-arm.c:optimized_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 3224710092,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:perf_trace_task_rename",
        "kernel/fork.c:perf_trace_task_newtask"
      ],
      "caller_func": []
    },
    {
      "addr": 3243360992,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_hotplug_init",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_state_remove_instance",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:__cpuhp_state_add_instance",
        "kernel/cpu.c:cpuhp_online_idle",
        "kernel/cpu.c:cpuhp_report_idle_dead",
        "kernel/cpu.c:take_cpu_down",
        "kernel/cpu.c:cpuhp_thread_fun",
        "kernel/cpu.c:cpuhp_should_run",
        "kernel/cpu.c:cpus_read_trylock",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/cpu.c:perf_trace_cpuhp_exit",
        "kernel/cpu.c:perf_trace_cpuhp_multi_enter",
        "kernel/cpu.c:perf_trace_cpuhp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3224742604,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3224748788,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:ksoftirqd_should_run",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:__raise_softirq_irqoff",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:__local_bh_enable_ip",
        "kernel/softirq.c:ksoftirqd_running",
        "kernel/softirq.c:wakeup_softirqd",
        "kernel/softirq.c:perf_trace_softirq",
        "kernel/softirq.c:perf_trace_irq_handler_exit",
        "kernel/softirq.c:perf_trace_irq_handler_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3224795460,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:perf_trace_signal_deliver",
        "kernel/signal.c:perf_trace_signal_generate"
      ],
      "caller_func": []
    },
    {
      "addr": 3224838472,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:perf_trace_workqueue_execute_start",
        "kernel/workqueue.c:perf_trace_workqueue_queue_work",
        "kernel/workqueue.c:perf_trace_workqueue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3224874280,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_associate_blkcg",
        "kernel/kthread.c:kthread_associate_blkcg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236535876,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:do_sched_yield",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:single_task_running",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi",
        "kernel/sched/core.c:perf_trace_sched_swap_numa",
        "kernel/sched/core.c:perf_trace_sched_move_task_template",
        "kernel/sched/core.c:perf_trace_sched_process_hang",
        "kernel/sched/core.c:perf_trace_sched_pi_setprio",
        "kernel/sched/core.c:perf_trace_sched_stat_runtime",
        "kernel/sched/core.c:perf_trace_sched_stat_template",
        "kernel/sched/core.c:perf_trace_sched_process_exec",
        "kernel/sched/core.c:perf_trace_sched_process_fork",
        "kernel/sched/core.c:perf_trace_sched_process_wait",
        "kernel/sched/core.c:perf_trace_sched_process_template",
        "kernel/sched/core.c:perf_trace_sched_migrate_task",
        "kernel/sched/core.c:perf_trace_sched_switch",
        "kernel/sched/core.c:perf_trace_sched_wakeup_template",
        "kernel/sched/core.c:perf_trace_sched_kthread_stop_ret",
        "kernel/sched/core.c:perf_trace_sched_kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3224955116,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_load_nohz_stop",
        "kernel/sched/loadavg.c:calc_load_nohz_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3224957780,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_process_tick",
        "kernel/sched/cputime.c:account_idle_time",
        "kernel/sched/cputime.c:account_idle_time",
        "kernel/sched/cputime.c:account_steal_time",
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 3224960008,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:sched_idle_set_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3224971292,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 3225021352,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rto_push_irq_work_func",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/rt.c:sched_rt_period_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3225023204,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:find_later_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 3225096156,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/cpuacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpuacct.c:cpuacct_account_field",
        "kernel/sched/cpuacct.c:cpuacct_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 3225096504,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq.c:cpufreq_this_cpu_can_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3225101864,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:membarrier_exec_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3225110152,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225117372,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/percpu-rwsem.c:__percpu_up_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3225118652,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/locking/osq_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225190940,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:defer_console_output",
        "kernel/printk/printk.c:defer_console_output",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk.c:perf_trace_console"
      ],
      "caller_func": []
    },
    {
      "addr": 3225193848,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:__printk_safe_exit",
        "kernel/printk/printk_safe.c:__printk_safe_enter",
        "kernel/printk/printk_safe.c:printk_nmi_direct_exit",
        "kernel/printk/printk_safe.c:printk_nmi_direct_enter",
        "kernel/printk/printk_safe.c:printk_nmi_direct_enter",
        "kernel/printk/printk_safe.c:printk_nmi_exit",
        "kernel/printk/printk_safe.c:printk_nmi_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225196824,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:__handle_domain_irq",
        "kernel/irq/irqdesc.c:__handle_domain_irq",
        "kernel/irq/irqdesc.c:__handle_domain_irq",
        "kernel/irq/irqdesc.c:__handle_domain_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3225197472,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/handle.c:handle_bad_irq",
        "kernel/irq/handle.c:handle_bad_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3225222608,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_devid_irq",
        "kernel/irq/chip.c:handle_percpu_irq",
        "kernel/irq/chip.c:handle_percpu_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_nmi",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq",
        "kernel/irq/chip.c:handle_simple_irq",
        "kernel/irq/chip.c:handle_nested_irq",
        "kernel/irq/chip.c:handle_nested_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3225251772,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:perf_trace_rcu_utilization"
      ],
      "caller_func": []
    },
    {
      "addr": 3225260192,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3225287436,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_needs_cpu",
        "kernel/rcu/tree.c:rcu_needs_cpu",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_fwd_progress_check",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_report_dead",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread",
        "kernel/rcu/tree.c:rcu_cpu_kthread_should_run",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcutree_dying_cpu",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter",
        "kernel/rcu/tree.c:rcu_nmi_enter",
        "kernel/rcu/tree.c:rcu_idle_exit",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225305356,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_tick"
      ],
      "caller_func": []
    },
    {
      "addr": 3225329476,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_dead_cpu",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/time/timer.c:run_local_timers",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:timer_clear_idle",
        "kernel/time/timer.c:get_next_timer_interrupt",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:timer_reduce",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:mod_timer_pending",
        "kernel/time/timer.c:perf_trace_tick_stop",
        "kernel/time/timer.c:perf_trace_itimer_expire",
        "kernel/time/timer.c:perf_trace_itimer_state",
        "kernel/time/timer.c:perf_trace_hrtimer_class",
        "kernel/time/timer.c:perf_trace_hrtimer_expire_entry",
        "kernel/time/timer.c:perf_trace_hrtimer_start",
        "kernel/time/timer.c:perf_trace_hrtimer_init",
        "kernel/time/timer.c:perf_trace_timer_expire_entry",
        "kernel/time/timer.c:perf_trace_timer_start",
        "kernel/time/timer.c:perf_trace_timer_class"
      ],
      "caller_func": []
    },
    {
      "addr": 3225339016,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:__hrtimer_init",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3225370348,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:perf_trace_alarm_class",
        "kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3225405516,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_suspend",
        "kernel/time/tick-common.c:tick_resume_local",
        "kernel/time/tick-common.c:tick_broadcast_oneshot_control",
        "kernel/time/tick-common.c:tick_install_replacement",
        "kernel/time/tick-common.c:tick_periodic",
        "kernel/time/tick-common.c:tick_is_oneshot_available"
      ],
      "caller_func": []
    },
    {
      "addr": 3225409984,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast",
        "kernel/time/tick-broadcast.c:tick_receive_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 3225412736,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-oneshot.c:tick_oneshot_mode_active",
        "kernel/time/tick-oneshot.c:tick_switch_to_oneshot",
        "kernel/time/tick-oneshot.c:tick_resume_oneshot",
        "kernel/time/tick-oneshot.c:tick_program_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3225419296,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_oneshot_notify",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_get_idle_calls",
        "kernel/time/tick-sched.c:tick_nohz_get_sleep_length",
        "kernel/time/tick-sched.c:tick_nohz_get_sleep_length",
        "kernel/time/tick-sched.c:tick_nohz_get_next_hrtimer",
        "kernel/time/tick-sched.c:tick_nohz_idle_got_tick",
        "kernel/time/tick-sched.c:tick_nohz_irq_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_retain_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/time/tick-sched.c:can_stop_idle_tick",
        "kernel/time/tick-sched.c:can_stop_idle_tick",
        "kernel/time/tick-sched.c:can_stop_idle_tick",
        "kernel/time/tick-sched.c:tick_nohz_next_event",
        "kernel/time/tick-sched.c:tick_nohz_tick_stopped"
      ],
      "caller_func": []
    },
    {
      "addr": 3225441540,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:smp_call_function_single",
        "kernel/smp.c:flush_smp_call_function_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3225456728,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:perf_trace_module_request",
        "kernel/module.c:perf_trace_module_refcnt",
        "kernel/module.c:perf_trace_module_free",
        "kernel/module.c:perf_trace_module_load"
      ],
      "caller_func": []
    },
    {
      "addr": 3225533600,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_event",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 3225536152,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/cgroup/rstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:__cgroup_account_cputime_field",
        "kernel/cgroup/rstat.c:__cgroup_account_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 3225545280,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3225551428,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3225556224,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge",
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 3225573544,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:cpuset_read_unlock",
        "kernel/cgroup/cpuset.c:cpuset_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225642280,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:aggr_fault_handler",
        "kernel/kprobes.c:aggr_post_handler",
        "kernel/kprobes.c:aggr_post_handler",
        "kernel/kprobes.c:aggr_pre_handler",
        "kernel/kprobes.c:aggr_pre_handler",
        "kernel/kprobes.c:opt_pre_handler",
        "kernel/kprobes.c:opt_pre_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3225660700,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_call_nmi_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 3225707700,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:softlockup_fn",
        "kernel/watchdog.c:softlockup_fn",
        "kernel/watchdog.c:softlockup_fn",
        "kernel/watchdog.c:is_hardlockup",
        "kernel/watchdog.c:is_hardlockup",
        "kernel/watchdog.c:is_hardlockup",
        "kernel/watchdog.c:touch_softlockup_watchdog_sync",
        "kernel/watchdog.c:touch_softlockup_watchdog_sync",
        "kernel/watchdog.c:__touch_watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 3225714736,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225732268,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:prepare_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 3225742496,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ignore_task_cpu",
        "kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe",
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ftrace.c:profile_graph_entry",
        "kernel/trace/ftrace.c:ftrace_pid_func"
      ],
      "caller_func": []
    },
    {
      "addr": 3225811264,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve",
        "kernel/trace/trace.c:disable_trace_buffered_event",
        "kernel/trace/trace.c:enable_trace_buffered_event",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 3225870020,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/trace_stack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_stack.c:t_stop",
        "kernel/trace/trace_stack.c:t_start",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_stack.c:stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 3225873812,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3225889484,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/trace/blktrace.c:trace_note"
      ],
      "caller_func": []
    },
    {
      "addr": 3225900356,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:ignore_task_cpu",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post",
        "kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre",
        "kernel/trace/trace_events.c:trace_event_buffer_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 3225913836,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:perf_syscall_exit",
        "kernel/trace/trace_syscalls.c:perf_syscall_enter",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225917728,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/trace_event_perf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_event_perf.c:perf_trace_buf_alloc",
        "kernel/trace/trace_event_perf.c:perf_trace_buf_alloc",
        "kernel/trace/trace_event_perf.c:perf_trace_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3225942576,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3225957480,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:kretprobe_dispatcher",
        "kernel/trace/trace_kprobe.c:kprobe_dispatcher",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ],
      "caller_func": []
    },
    {
      "addr": 3225969636,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/power-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request",
        "kernel/trace/power-traces.c:perf_trace_pm_qos_update",
        "kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout",
        "kernel/trace/power-traces.c:perf_trace_pm_qos_request",
        "kernel/trace/power-traces.c:perf_trace_power_domain",
        "kernel/trace/power-traces.c:perf_trace_clock",
        "kernel/trace/power-traces.c:perf_trace_wakeup_source",
        "kernel/trace/power-traces.c:perf_trace_suspend_resume",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_end",
        "kernel/trace/power-traces.c:perf_trace_device_pm_callback_start",
        "kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits",
        "kernel/trace/power-traces.c:perf_trace_pstate_sample",
        "kernel/trace/power-traces.c:perf_trace_powernv_throttle",
        "kernel/trace/power-traces.c:perf_trace_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3225976552,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/rpm-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/rpm-traces.c:perf_trace_rpm_return_int",
        "kernel/trace/rpm-traces.c:perf_trace_rpm_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 3225989760,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func",
        "kernel/trace/trace_uprobe.c:__uprobe_trace_func"
      ],
      "caller_func": []
    },
    {
      "addr": 3226002672,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq_work.c:irq_work_tick",
        "kernel/irq_work.c:irq_work_tick",
        "kernel/irq_work.c:irq_work_run",
        "kernel/irq_work.c:irq_work_run",
        "kernel/irq_work.c:irq_work_needs_cpu",
        "kernel/irq_work.c:irq_work_needs_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3226008092,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:perf_trace_mem_return_failed",
        "kernel/bpf/core.c:perf_trace_mem_connect",
        "kernel/bpf/core.c:perf_trace_mem_disconnect",
        "kernel/bpf/core.c:perf_trace_xdp_devmap_xmit",
        "kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:perf_trace_xdp_redirect_template",
        "kernel/bpf/core.c:perf_trace_xdp_bulk_tx",
        "kernel/bpf/core.c:perf_trace_xdp_exception",
        "kernel/bpf/core.c:bpf_user_rnd_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 3226041272,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226110488,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_get_local_storage",
        "kernel/bpf/helpers.c:bpf_get_local_storage",
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:bpf_spin_unlock",
        "kernel/bpf/helpers.c:bpf_spin_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3226120444,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_elem_free_rcu",
        "kernel/bpf/hashtab.c:htab_elem_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3226129204,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/arraymap.c:percpu_array_map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226131608,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push"
      ],
      "caller_func": []
    },
    {
      "addr": 3226167828,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3226175548,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 3226177344,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:__xsk_map_flush",
        "kernel/bpf/xskmap.c:__xsk_map_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 3226182184,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "kernel/bpf/offload.c:bpf_prog_offload_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3226186048,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 3226195584,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 3226255768,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:__perf_event_exit_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_cancel_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_commit_txn",
        "kernel/events/core.c:perf_pmu_start_txn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:perf_tp_event",
        "kernel/events/core.c:perf_swevent_add",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:__perf_sw_event",
        "kernel/events/core.c:___perf_sw_event",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:__perf_pmu_output_stop",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_iterate_sb",
        "kernel/events/core.c:perf_pending_event",
        "kernel/events/core.c:perf_pending_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:perf_event_task_tick",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_in",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:perf_pmu_sched_task",
        "kernel/events/core.c:perf_sched_cb_inc",
        "kernel/events/core.c:perf_sched_cb_inc",
        "kernel/events/core.c:perf_sched_cb_inc",
        "kernel/events/core.c:perf_sched_cb_dec",
        "kernel/events/core.c:perf_sched_cb_dec",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_enable",
        "kernel/events/core.c:__perf_install_in_context",
        "kernel/events/core.c:perf_pmu_resched",
        "kernel/events/core.c:event_sched_in",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:perf_group_detach",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:list_add_event",
        "kernel/events/core.c:perf_cgroup_switch",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/core.c:event_function"
      ],
      "caller_func": []
    },
    {
      "addr": 3226284088,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 3226297728,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_end_dup_mmap",
        "kernel/events/uprobes.c:uprobe_start_dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226309020,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:perf_trace_rseq_ip_fixup",
        "kernel/rseq.c:perf_trace_rseq_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3226335632,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:perf_trace_file_check_and_advance_wb_err",
        "mm/filemap.c:perf_trace_filemap_set_wb_err",
        "mm/filemap.c:perf_trace_mm_filemap_op_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3226355728,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:perf_trace_compact_retry",
        "mm/oom_kill.c:perf_trace_skip_task_reaping",
        "mm/oom_kill.c:perf_trace_finish_task_reaping",
        "mm/oom_kill.c:perf_trace_start_task_reaping",
        "mm/oom_kill.c:perf_trace_wake_reaper",
        "mm/oom_kill.c:perf_trace_mark_victim",
        "mm/oom_kill.c:perf_trace_reclaim_retry_zone",
        "mm/oom_kill.c:perf_trace_oom_score_adj_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3226379380,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 3226391516,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:pagevec_move_tail",
        "mm/swap.c:perf_trace_mm_lru_activate",
        "mm/swap.c:perf_trace_mm_lru_insertion"
      ],
      "caller_func": []
    },
    {
      "addr": 3226437260,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin",
        "mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active",
        "mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:perf_trace_mm_vmscan_writepage",
        "mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate",
        "mm/vmscan.c:perf_trace_mm_shrink_slab_end",
        "mm/vmscan.c:perf_trace_mm_shrink_slab_start",
        "mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template",
        "mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd",
        "mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake",
        "mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 3226450560,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226478584,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:quiet_vmstat",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:vm_events_fold_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3226485736,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226490292,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:perf_trace_percpu_destroy_chunk",
        "mm/percpu.c:perf_trace_percpu_create_chunk",
        "mm/percpu.c:perf_trace_percpu_alloc_percpu_fail",
        "mm/percpu.c:perf_trace_percpu_free_percpu",
        "mm/percpu.c:perf_trace_percpu_alloc_percpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3226515640,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params",
        "mm/slab_common.c:perf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:perf_trace_mm_page_pcpu_drain",
        "mm/slab_common.c:perf_trace_mm_page",
        "mm/slab_common.c:perf_trace_mm_page_alloc",
        "mm/slab_common.c:perf_trace_mm_page_free_batched",
        "mm/slab_common.c:perf_trace_mm_page_free",
        "mm/slab_common.c:perf_trace_kmem_free",
        "mm/slab_common.c:perf_trace_kmem_alloc_node",
        "mm/slab_common.c:perf_trace_kmem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226537568,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:perf_trace_kcompactd_wake_template",
        "mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep",
        "mm/compaction.c:perf_trace_mm_compaction_defer_template",
        "mm/compaction.c:perf_trace_mm_compaction_suitable_template",
        "mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages",
        "mm/compaction.c:perf_trace_mm_compaction_end",
        "mm/compaction.c:perf_trace_mm_compaction_begin",
        "mm/compaction.c:perf_trace_mm_compaction_migratepages",
        "mm/compaction.c:perf_trace_mm_compaction_isolate_template"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226582124,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226586968,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mlock.c:clear_page_mlock"
      ],
      "caller_func": []
    },
    {
      "addr": 3226644932,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:vm_map_ram",
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 3226682100,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:show_free_areas",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_commit",
        "mm/page_alloc.c:free_unref_page_commit",
        "mm/page_alloc.c:__free_pages_ok"
      ],
      "caller_func": []
    },
    {
      "addr": 3226702856,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 3226708744,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3226717040,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/swapfile.c:scan_swap_map_try_ssd_cluster"
      ],
      "caller_func": []
    },
    {
      "addr": 3226732224,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:free_swap_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 3226739032,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3226796524,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226807156,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:perf_trace_mm_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226847972,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:refill_stock",
        "mm/memcontrol.c:drain_local_stock",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3226854780,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:perf_trace_test_pages_isolated"
      ],
      "caller_func": []
    },
    {
      "addr": 3226868516,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 3226871408,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:perf_trace_cma_release",
        "mm/cma.c:perf_trace_cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226874924,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 3226887604,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 3226896116,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:perf_trace_open_exec",
        "fs/open.c:perf_trace_do_sys_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3226923492,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:__sb_end_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3226947380,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 3227026520,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:__d_instantiate",
        "fs/dcache.c:__d_alloc",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:dentry_lru_isolate",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_lru_shrink_move",
        "fs/dcache.c:d_shrink_add",
        "fs/dcache.c:d_shrink_del",
        "fs/dcache.c:d_lru_del",
        "fs/dcache.c:d_lru_del",
        "fs/dcache.c:d_lru_add",
        "fs/dcache.c:d_lru_add",
        "fs/dcache.c:dentry_unlink_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3227043152,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:inode_lru_list_add",
        "fs/inode.c:__destroy_inode",
        "fs/inode.c:__destroy_inode",
        "fs/inode.c:inode_init_always"
      ],
      "caller_func": []
    },
    {
      "addr": 3227093000,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:mnt_set_mountpoint",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_clone_write",
        "fs/namespace.c:__mnt_want_write",
        "fs/namespace.c:__mnt_want_write",
        "fs/namespace.c:alloc_vfsmnt"
      ],
      "caller_func": []
    },
    {
      "addr": 3227152464,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:perf_trace_writeback_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_congest_waited_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_global_dirty_state",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_pages_written",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template"
      ],
      "caller_func": []
    },
    {
      "addr": 3227195028,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:buffer_exit_cpu_dead",
        "fs/buffer.c:alloc_buffer_head",
        "fs/buffer.c:invalidate_bh_lru",
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 3227228464,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3227256420,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3227297164,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_signal",
        "fs/eventfd.c:eventfd_signal",
        "fs/eventfd.c:eventfd_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 3227319056,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__se_sys_io_cancel",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:lookup_ioctx",
        "fs/aio.c:__get_reqs_available",
        "fs/aio.c:put_reqs_available",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 3227349580,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 3227409612,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:locks_remove_file",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:fcntl_getlease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:__break_lease",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:posix_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:flock_lock_inode",
        "fs/locks.c:locks_insert_global_locks",
        "fs/locks.c:perf_trace_leases_conflict",
        "fs/locks.c:perf_trace_generic_add_lease",
        "fs/locks.c:perf_trace_filelock_lease",
        "fs/locks.c:perf_trace_filelock_lock",
        "fs/locks.c:perf_trace_locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3227458872,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/drop_caches.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/drop_caches.c:drop_caches_sysctl_handler",
        "fs/drop_caches.c:drop_caches_sysctl_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3227805172,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": []
    },
    {
      "addr": 3227842460,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3227978544,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_error",
        "fs/ext4/super.c:perf_trace_ext4_shutdown",
        "fs/ext4/super.c:perf_trace_ext4_getfsmap_class",
        "fs/ext4/super.c:perf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block",
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:perf_trace_ext4_insert_range",
        "fs/ext4/super.c:perf_trace_ext4_collapse_range",
        "fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit",
        "fs/ext4/super.c:perf_trace_ext4__es_shrink_enter",
        "fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit",
        "fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter",
        "fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit",
        "fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter",
        "fs/ext4/super.c:perf_trace_ext4_es_remove_extent",
        "fs/ext4/super.c:perf_trace_ext4__es_extent",
        "fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:perf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:perf_trace_ext4_ext_rm_idx",
        "fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:perf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:perf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc",
        "fs/ext4/super.c:perf_trace_ext4_find_delalloc_range",
        "fs/ext4/super.c:perf_trace_ext4_ext_in_cache",
        "fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit",
        "fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:perf_trace_ext4__trim",
        "fs/ext4/super.c:perf_trace_ext4_journal_start_reserved",
        "fs/ext4/super.c:perf_trace_ext4_journal_start",
        "fs/ext4/super.c:perf_trace_ext4_load_inode",
        "fs/ext4/super.c:perf_trace_ext4_ext_load_extent",
        "fs/ext4/super.c:perf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:perf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter",
        "fs/ext4/super.c:perf_trace_ext4__truncate",
        "fs/ext4/super.c:perf_trace_ext4_unlink_exit",
        "fs/ext4/super.c:perf_trace_ext4_unlink_enter",
        "fs/ext4/super.c:perf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:perf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:perf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:perf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:perf_trace_ext4__bitmap_load",
        "fs/ext4/super.c:perf_trace_ext4_da_release_space",
        "fs/ext4/super.c:perf_trace_ext4_da_reserve_space",
        "fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space",
        "fs/ext4/super.c:perf_trace_ext4_forget",
        "fs/ext4/super.c:perf_trace_ext4__mballoc",
        "fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc",
        "fs/ext4/super.c:perf_trace_ext4_mballoc_alloc",
        "fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks",
        "fs/ext4/super.c:perf_trace_ext4_sync_fs",
        "fs/ext4/super.c:perf_trace_ext4_sync_file_exit",
        "fs/ext4/super.c:perf_trace_ext4_sync_file_enter",
        "fs/ext4/super.c:perf_trace_ext4_free_blocks",
        "fs/ext4/super.c:perf_trace_ext4_allocate_blocks",
        "fs/ext4/super.c:perf_trace_ext4_request_blocks",
        "fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations",
        "fs/ext4/super.c:perf_trace_ext4_discard_preallocations",
        "fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa",
        "fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa",
        "fs/ext4/super.c:perf_trace_ext4__mb_new_pa",
        "fs/ext4/super.c:perf_trace_ext4_discard_blocks",
        "fs/ext4/super.c:perf_trace_ext4_invalidatepage_op",
        "fs/ext4/super.c:perf_trace_ext4__page_op",
        "fs/ext4/super.c:perf_trace_ext4_writepages_result",
        "fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent",
        "fs/ext4/super.c:perf_trace_ext4_da_write_pages",
        "fs/ext4/super.c:perf_trace_ext4_writepages",
        "fs/ext4/super.c:perf_trace_ext4__write_end",
        "fs/ext4/super.c:perf_trace_ext4__write_begin",
        "fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate",
        "fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty",
        "fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata",
        "fs/ext4/super.c:perf_trace_ext4_drop_inode",
        "fs/ext4/super.c:perf_trace_ext4_evict_inode",
        "fs/ext4/super.c:perf_trace_ext4_allocate_inode",
        "fs/ext4/super.c:perf_trace_ext4_request_inode",
        "fs/ext4/super.c:perf_trace_ext4_free_inode",
        "fs/ext4/super.c:perf_trace_ext4_other_inode_update_time"
      ],
      "caller_func": []
    },
    {
      "addr": 3228131164,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall",
        "fs/jbd2/journal.c:perf_trace_jbd2_write_superblock",
        "fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail",
        "fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:perf_trace_jbd2_run_stats",
        "fs/jbd2/journal.c:perf_trace_jbd2_handle_stats",
        "fs/jbd2/journal.c:perf_trace_jbd2_handle_extend",
        "fs/jbd2/journal.c:perf_trace_jbd2_handle_start",
        "fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data",
        "fs/jbd2/journal.c:perf_trace_jbd2_end_commit",
        "fs/jbd2/journal.c:perf_trace_jbd2_commit",
        "fs/jbd2/journal.c:perf_trace_jbd2_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 3228550768,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_node_kill",
        "security/selinux/avc.c:avc_node_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3228618416,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "security/selinux/netif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/netif.c:sel_netif_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 3228737608,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "security/lsm_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/lsm_audit.c:dump_common_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3228824484,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "security/apparmor/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/capability.c:aa_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 3228849260,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:profile_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 3228896552,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_file_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 3228920200,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "security/apparmor/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": []
    },
    {
      "addr": 3229031648,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "crypto/scompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ],
      "caller_func": []
    },
    {
      "addr": 3229123380,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_associate_blkg",
        "block/bio.c:__bio_associate_blkg"
      ],
      "caller_func": []
    },
    {
      "addr": 3229160936,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:blk_queue_enter",
        "block/blk-core.c:blk_queue_enter",
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_unplug",
        "block/blk-core.c:perf_trace_block_plug",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:perf_trace_block_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3229187180,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229189628,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "block/blk-softirq.c:blk_done_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 3229200076,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3229221756,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3229224100,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3229231192,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 3229323404,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3229335900,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued",
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 3229354036,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj",
        "block/blk-iocost.c:perf_trace_iocg_inuse_update",
        "block/blk-iocost.c:perf_trace_iocost_iocg_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 3229385136,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:perf_trace_wbt_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:perf_trace_wbt_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 3229423280,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 3229463740,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3229647244,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_add_batch",
        "lib/percpu_counter.c:percpu_counter_add_batch",
        "lib/percpu_counter.c:percpu_counter_add_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 3229680376,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq"
      ],
      "caller_func": []
    },
    {
      "addr": 3229691100,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get_shallow",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "lib/sbitmap.c:__sbitmap_queue_get",
        "lib/sbitmap.c:__sbitmap_queue_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3229702828,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gic_cpu_restore",
        "drivers/irqchip/irq-gic.c:gic_cpu_restore",
        "drivers/irqchip/irq-gic.c:gic_cpu_restore",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_save",
        "drivers/irqchip/irq-gic.c:gic_cpu_save"
      ],
      "caller_func": []
    },
    {
      "addr": 3229712536,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_set_affinity",
        "drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist",
        "drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist",
        "drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist",
        "drivers/irqchip/irq-gic-v3.c:gic_set_type",
        "drivers/irqchip/irq-gic-v3.c:gic_poke_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_peek_irq",
        "drivers/irqchip/irq-gic-v3.c:gic_redist_wait_for_rwp"
      ],
      "caller_func": []
    },
    {
      "addr": 3243559988,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis"
      ],
      "caller_func": []
    },
    {
      "addr": 3229995324,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:perf_trace_gpio_value",
        "drivers/gpio/gpiolib.c:perf_trace_gpio_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 3230590228,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:perf_trace_clk_duty_cycle",
        "drivers/clk/clk.c:perf_trace_clk_phase",
        "drivers/clk/clk.c:perf_trace_clk_parent",
        "drivers/clk/clk.c:perf_trace_clk_rate",
        "drivers/clk/clk.c:perf_trace_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 3230783236,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_find_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 3230844672,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/dma/tegra20-apb-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_isr",
        "drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_complete_cb",
        "drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_tx_status"
      ],
      "caller_func": []
    },
    {
      "addr": 3230891688,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/soc/qcom/spm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/spm.c:qcom_idle_enter",
        "drivers/soc/qcom/spm.c:qcom_cpu_spc"
      ],
      "caller_func": []
    },
    {
      "addr": 3230954988,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 3230976828,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:perf_trace_regulator_value",
        "drivers/regulator/core.c:perf_trace_regulator_range",
        "drivers/regulator/core.c:perf_trace_regulator_basic"
      ],
      "caller_func": []
    },
    {
      "addr": 3231094376,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_showregs"
      ],
      "caller_func": []
    },
    {
      "addr": 3231116984,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ],
      "caller_func": []
    },
    {
      "addr": 3231360872,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u32",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:add_interrupt_randomness",
        "drivers/char/random.c:perf_trace_urandom_read",
        "drivers/char/random.c:perf_trace_random_read",
        "drivers/char/random.c:perf_trace_random__extract_entropy",
        "drivers/char/random.c:perf_trace_random__get_random_bytes",
        "drivers/char/random.c:perf_trace_xfer_secondary_pool",
        "drivers/char/random.c:perf_trace_add_disk_randomness",
        "drivers/char/random.c:perf_trace_add_input_randomness",
        "drivers/char/random.c:perf_trace_debit_entropy",
        "drivers/char/random.c:perf_trace_push_to_pool",
        "drivers/char/random.c:perf_trace_credit_entropy_bits",
        "drivers/char/random.c:perf_trace_random__mix_pool_bytes",
        "drivers/char/random.c:perf_trace_add_device_randomness"
      ],
      "caller_func": []
    },
    {
      "addr": 3231446464,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/iommu/iommu-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_error",
        "drivers/iommu/iommu-traces.c:perf_trace_unmap",
        "drivers/iommu/iommu-traces.c:perf_trace_map",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event",
        "drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3231505004,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/connector/cn_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/connector/cn_proc.c:proc_exit_connector",
        "drivers/connector/cn_proc.c:proc_coredump_connector",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/connector/cn_proc.c:proc_ptrace_connector",
        "drivers/connector/cn_proc.c:proc_sid_connector",
        "drivers/connector/cn_proc.c:proc_id_connector",
        "drivers/connector/cn_proc.c:proc_exec_connector",
        "drivers/connector/cn_proc.c:proc_fork_connector"
      ],
      "caller_func": []
    },
    {
      "addr": 3231682464,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_async",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_bool",
        "drivers/base/regmap/regmap.c:perf_trace_regcache_sync",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_block",
        "drivers/base/regmap/regmap.c:perf_trace_regmap_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 3231743244,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231964988,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:perf_trace_dma_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 3231979220,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline"
      ],
      "caller_func": []
    },
    {
      "addr": 3231983524,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/scsi/scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup",
        "drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template",
        "drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error",
        "drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3232022624,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3232130980,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc",
        "drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy",
        "drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template",
        "drivers/ata/libata-core.c:perf_trace_ata_qc_issue"
      ],
      "caller_func": []
    },
    {
      "addr": 3232436760,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:perf_trace_spi_transfer",
        "drivers/spi/spi.c:perf_trace_spi_message_done",
        "drivers/spi/spi.c:perf_trace_spi_message",
        "drivers/spi/spi.c:perf_trace_spi_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 3232466156,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3232490600,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:perf_trace_mdio_access"
      ],
      "caller_func": []
    },
    {
      "addr": 3232503140,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_show_fdinfo",
        "drivers/net/tun.c:tun_chr_show_fdinfo",
        "drivers/net/tun.c:tun_peek_len",
        "drivers/net/tun.c:tun_peek_len",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_chr_read_iter",
        "drivers/net/tun.c:tun_chr_read_iter",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_do_read",
        "drivers/net/tun.c:tun_chr_write_iter",
        "drivers/net/tun.c:tun_chr_write_iter",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/tun.c:tun_chr_poll",
        "drivers/net/tun.c:tun_chr_poll",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3232575768,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/net/ethernet/ti/cpsw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3232620788,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process",
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3233131672,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx",
        "drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 3233185332,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/usb/musb/musb_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_trace.c:perf_trace_musb_req",
        "drivers/usb/musb/musb_trace.c:perf_trace_musb_urb",
        "drivers/usb/musb/musb_trace.c:perf_trace_musb_isr",
        "drivers/usb/musb/musb_trace.c:perf_trace_musb_regl",
        "drivers/usb/musb/musb_trace.c:perf_trace_musb_regw",
        "drivers/usb/musb/musb_trace.c:perf_trace_musb_regb",
        "drivers/usb/musb/musb_trace.c:perf_trace_musb_log"
      ],
      "caller_func": []
    },
    {
      "addr": 3233237136,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/usb/gadget/udc/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_req",
        "drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_ep",
        "drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_gadget"
      ],
      "caller_func": []
    },
    {
      "addr": 3233309688,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/rtc/interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/interface.c:perf_trace_rtc_timer_class",
        "drivers/rtc/interface.c:perf_trace_rtc_offset_class",
        "drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable",
        "drivers/rtc/interface.c:perf_trace_rtc_irq_set_state",
        "drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq",
        "drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class"
      ],
      "caller_func": []
    },
    {
      "addr": 3233350276,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:perf_trace_i2c_result",
        "drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply",
        "drivers/i2c/i2c-core-base.c:perf_trace_i2c_read",
        "drivers/i2c/i2c-core-base.c:perf_trace_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3233367456,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result",
        "drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply",
        "drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read",
        "drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3233488924,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string",
        "drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class"
      ],
      "caller_func": []
    },
    {
      "addr": 3233501924,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip",
        "drivers/thermal/thermal_core.c:perf_trace_cdev_update",
        "drivers/thermal/thermal_core.c:perf_trace_thermal_temperature"
      ],
      "caller_func": []
    },
    {
      "addr": 3233524792,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid",
        "drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator"
      ],
      "caller_func": []
    },
    {
      "addr": 3233598604,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 3233726872,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 3233814800,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 3233823720,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/cpuidle/governors/ladder.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3233824188,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_reflect",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 3233832864,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/cpuidle/cpuidle-psci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233844640,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:perf_trace_mmc_request_done",
        "drivers/mmc/core/core.c:perf_trace_mmc_request_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3234022536,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3243948824,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/clocksource/timer-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-tegra.c:tegra_init_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3234116408,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3234118096,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/clocksource/arm_global_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_global_timer.c:gt_dying_cpu",
        "drivers/clocksource/arm_global_timer.c:gt_starting_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3234198364,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/platform/chrome/cros_ec_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class"
      ],
      "caller_func": []
    },
    {
      "addr": 3234240244,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor"
      ],
      "caller_func": []
    },
    {
      "addr": 3234326600,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu.c:cpu_pm_pmu_notify",
        "drivers/perf/arm_pmu.c:cpu_pm_pmu_setup",
        "drivers/perf/arm_pmu.c:armpmu_enable",
        "drivers/perf/arm_pmu.c:armpmu_add",
        "drivers/perf/arm_pmu.c:armpmu_del"
      ],
      "caller_func": []
    },
    {
      "addr": 3234331168,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "drivers/ras/ras.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/ras.c:perf_trace_aer_event",
        "drivers/ras/ras.c:perf_trace_non_standard_event",
        "drivers/ras/ras.c:perf_trace_arm_event",
        "drivers/ras/ras.c:perf_trace_mc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3234482688,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "sound/soc/soc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/soc-core.c:perf_trace_snd_soc_jack_notify",
        "sound/soc/soc-core.c:perf_trace_snd_soc_jack_report",
        "sound/soc/soc-core.c:perf_trace_snd_soc_jack_irq",
        "sound/soc/soc-core.c:perf_trace_snd_soc_dapm_connected",
        "sound/soc/soc-core.c:perf_trace_snd_soc_dapm_path",
        "sound/soc/soc-core.c:perf_trace_snd_soc_dapm_walk_done",
        "sound/soc/soc-core.c:perf_trace_snd_soc_dapm_widget",
        "sound/soc/soc-core.c:perf_trace_snd_soc_dapm_basic",
        "sound/soc/soc-core.c:perf_trace_snd_soc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 3234626144,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_prot_inuse_add",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:__sk_free",
        "net/core/sock.c:sk_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3234685992,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:netdev_alloc_frag",
        "net/core/skbuff.c:napi_alloc_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 3234719988,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 3234801384,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:__napi_schedule_irqoff",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:flush_backlog",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_hard_start_xmit",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/core/dev.c:dev_getfirstbyhwtype",
        "net/core/dev.c:dev_get_by_index",
        "net/core/dev.c:dev_get_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 3234821288,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 3234834748,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_dev_put",
        "net/core/dst.c:dst_dev_put",
        "net/core/dst.c:dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 3234844544,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_invalidate",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:pneigh_delete",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_lookup_nodev",
        "net/core/neighbour.c:neigh_lookup_nodev",
        "net/core/neighbour.c:neigh_lookup",
        "net/core/neighbour.c:neigh_lookup",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:pneigh_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 3234905112,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/utils.c:inet6_pton"
      ],
      "caller_func": []
    },
    {
      "addr": 3234907008,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_do_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3234973720,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/core/filter.c:bpf_skb_set_tunnel_opt",
        "net/core/filter.c:bpf_skb_set_tunnel_key",
        "net/core/filter.c:bpf_xdp_redirect_map",
        "net/core/filter.c:bpf_xdp_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_generic_redirect",
        "net/core/filter.c:xdp_do_redirect",
        "net/core/filter.c:xdp_do_flush_map",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:bpf_csum_diff",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 3234980768,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3234988476,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 3235005868,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:netdev_queue_release",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects",
        "net/core/net-sysfs.c:rx_queue_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3235014700,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_bpf_run",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 3235023072,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_cleanup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3235050208,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_neigh__update",
        "net/core/net-traces.c:perf_trace_neigh_update",
        "net/core/net-traces.c:perf_trace_neigh_create",
        "net/core/net-traces.c:perf_trace_page_pool_state_hold",
        "net/core/net-traces.c:perf_trace_page_pool_state_release",
        "net/core/net-traces.c:perf_trace_page_pool_inflight",
        "net/core/net-traces.c:perf_trace_br_fdb_update",
        "net/core/net-traces.c:perf_trace_fdb_delete",
        "net/core/net-traces.c:perf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:perf_trace_br_fdb_add",
        "net/core/net-traces.c:perf_trace_qdisc_dequeue",
        "net/core/net-traces.c:perf_trace_fib_table_lookup",
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_retransmit_synack",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:perf_trace_tcp_event_sk_skb",
        "net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb",
        "net/core/net-traces.c:perf_trace_inet_sock_set_state",
        "net/core/net-traces.c:perf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:perf_trace_sock_rcvqueue_full",
        "net/core/net-traces.c:perf_trace_napi_poll",
        "net/core/net-traces.c:perf_trace_net_dev_rx_exit_template",
        "net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template",
        "net/core/net-traces.c:perf_trace_net_dev_template",
        "net/core/net-traces.c:perf_trace_net_dev_xmit_timeout",
        "net/core/net-traces.c:perf_trace_net_dev_xmit",
        "net/core/net-traces.c:perf_trace_net_dev_start_xmit",
        "net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec",
        "net/core/net-traces.c:perf_trace_consume_skb",
        "net/core/net-traces.c:perf_trace_kfree_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235063712,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_metadata_free",
        "net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit",
        "net/core/drop_monitor.c:net_dm_hw_summary_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3235073260,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235074552,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/netprio_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netprio_cgroup.c:write_priomap"
      ],
      "caller_func": []
    },
    {
      "addr": 3235079148,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3235092000,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_get_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4",
        "net/core/dst_cache.c:dst_cache_get_ip4",
        "net/core/dst_cache.c:dst_cache_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3235149492,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_trap_stats_update",
        "net/core/devlink.c:perf_trace_devlink_health_reporter_state_update",
        "net/core/devlink.c:perf_trace_devlink_health_recover_aborted",
        "net/core/devlink.c:perf_trace_devlink_health_report",
        "net/core/devlink.c:perf_trace_devlink_hwerr",
        "net/core/devlink.c:perf_trace_devlink_hwmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3235150356,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro_cells.c:gro_cells_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3235169092,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:pfifo_fast_dequeue",
        "net/sched/sch_generic.c:pfifo_fast_dequeue",
        "net/sched/sch_generic.c:pfifo_fast_dequeue",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
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
      "addr": 3235176868,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3235233824,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 3235261308,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:perf_trace_bpf_test_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 3235272028,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 3235301424,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:ip_handle_martian_source",
        "net/ipv4/route.c:rt_flush_dev",
        "net/ipv4/route.c:rt_flush_dev",
        "net/ipv4/route.c:rt_add_uncached_list",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_error"
      ],
      "caller_func": []
    },
    {
      "addr": 3235305632,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu",
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3235312928,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/ip_fragment.c:ip_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 3235314960,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/ip_forward.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward",
        "net/ipv4/ip_forward.c:ip_forward_finish",
        "net/ipv4/ip_forward.c:ip_forward_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 3235337080,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_send_skb",
        "net/ipv4/ip_output.c:ip_append_page",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:ip_do_fragment",
        "net/ipv4/ip_output.c:__ip_queue_xmit",
        "net/ipv4/ip_output.c:ip_output",
        "net/ipv4/ip_output.c:ip_mc_output",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/ip_output.c:ip_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 3235348588,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235353532,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 3235359936,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:tw_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3235362044,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_route_req"
      ],
      "caller_func": []
    },
    {
      "addr": 3235376452,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_push"
      ],
      "caller_func": []
    },
    {
      "addr": 3235413776,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_syn_flood_action",
        "net/ipv4/tcp_input.c:tcp_syn_flood_action",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_newly_delivered",
        "net/ipv4/tcp_input.c:tcp_newly_delivered",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_enter_recovery",
        "net/ipv4/tcp_input.c:tcp_try_undo_recovery",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_input.c:tcp_check_reno_reordering",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235463716,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 3235477164,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_syn_ack_timeout",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_err"
      ],
      "caller_func": []
    },
    {
      "addr": 3235502024,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 3235507596,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3235523080,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 3235524216,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_mark_skb_lost"
      ],
      "caller_func": []
    },
    {
      "addr": 3235530844,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 3235535820,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235563320,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:udp_send_skb",
        "net/ipv4/udp.c:__udp4_lib_err"
      ],
      "caller_func": []
    },
    {
      "addr": 3235575696,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3235583920,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:icmp_unreach",
        "net/ipv4/icmp.c:__icmp_send",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/icmp.c:icmp_push_reply",
        "net/ipv4/icmp.c:icmp_out_count"
      ],
      "caller_func": []
    },
    {
      "addr": 3235600124,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_init",
        "net/ipv4/devinet.c:in_dev_finish_destroy",
        "net/ipv4/devinet.c:__ip_dev_find"
      ],
      "caller_func": []
    },
    {
      "addr": 3235606700,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net",
        "net/ipv4/af_inet.c:ipv4_mib_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 3235655380,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_semantics.c:fib_check_nh_v6_gw",
        "net/ipv4/fib_semantics.c:fib_nh_common_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3235675576,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ],
      "caller_func": []
    },
    {
      "addr": 3235695864,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_v4_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3235700372,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:iptunnel_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3235739172,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 3235757924,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3235760876,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_acked"
      ],
      "caller_func": []
    },
    {
      "addr": 3235778344,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:xfrm4_fill_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 3235784224,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_ifdown",
        "net/xfrm/xfrm_policy.c:xfrm_dst_ifdown",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle",
        "net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle"
      ],
      "caller_func": []
    },
    {
      "addr": 3235822568,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 3235847808,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_trans_queue",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3235858156,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3235864040,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": []
    },
    {
      "addr": 3235900156,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:__ip6_flush_pending_frames",
        "net/ipv6/ip6_output.c:ip6_send_skb",
        "net/ipv6/ip6_output.c:ip6_send_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_fragment",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_output",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/ip6_output.c:ip6_finish_output2"
      ],
      "caller_func": []
    },
    {
      "addr": 3235928192,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_mc_input",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ],
      "caller_func": []
    },
    {
      "addr": 3235965880,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 3236023652,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:ip6_pkt_drop",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:rt6_probe_deferred",
        "net/ipv6/route.c:rt6_uncached_list_add",
        "net/ipv6/route.c:perf_trace_fib6_table_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3236054008,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236063304,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236074336,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:udp_v6_send_skb",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236092560,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 3236104760,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ],
      "caller_func": []
    },
    {
      "addr": 3236116108,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack"
      ],
      "caller_func": []
    },
    {
      "addr": 3236133572,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_reasm",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_queue",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/reassembly.c:ip6_frag_expire",
        "net/ipv6/reassembly.c:ip6_frag_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 3236149736,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ],
      "caller_func": []
    },
    {
      "addr": 3236154024,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236155608,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_hop_jumbo",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_srh_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv",
        "net/ipv6/exthdrs.c:ipv6_destopt_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236194716,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236208200,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 3236210060,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/xfrm6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 3236211344,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/xfrm6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_output.c:__xfrm6_output",
        "net/ipv6/xfrm6_output.c:xfrm6_extract_output"
      ],
      "caller_func": []
    },
    {
      "addr": 3236214648,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/netfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ],
      "caller_func": []
    },
    {
      "addr": 3236223232,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3236242272,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh"
      ],
      "caller_func": []
    },
    {
      "addr": 3244008536,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_init",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ],
      "caller_func": []
    },
    {
      "addr": 3236247352,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf_core.c:in6_dev_finish_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 3236259420,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ],
      "caller_func": []
    },
    {
      "addr": 3236264912,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 3236298388,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/8021q/vlan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/8021q/vlan_core.c:vlan_do_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3236324856,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3236364904,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/switchdev/switchdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/switchdev/switchdev.c:switchdev_deferred_enqueue",
        "net/switchdev/switchdev.c:switchdev_deferred_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3236393464,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex"
      ],
      "caller_func": []
    },
    {
      "addr": 3236400596,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3236410752,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_clear_dev",
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3236464756,
      "name": "__my_cpu_offset",
      "external": false,
      "loc": "arch/arm/include/asm/percpu.h:19",
      "file": "lib/radix-tree.c",
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
long unsigned int __my_cpu_offset()
```
</details>
</li>
</ul>

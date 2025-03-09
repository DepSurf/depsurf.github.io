# Function: <code>__range_ok</code>

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
long unsigned int __range_ok(const void * addr, long unsigned int size)
```

```json
{
  "name": "__range_ok",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490181660,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kernel/debug-monitors.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/debug-monitors.c:aarch32_break_handler",
        "arch/arm64/kernel/debug-monitors.c:aarch32_break_handler",
        "arch/arm64/kernel/debug-monitors.c:aarch32_break_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490214992,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_gpr_set",
        "arch/arm64/kernel/ptrace.c:compat_gpr_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get"
      ],
      "caller_func": [
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:sve_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get"
      ]
    },
    {
      "addr": 18446603336490228568,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/signal.c:setup_rt_frame",
        "arch/arm64/kernel/signal.c:setup_rt_frame",
        "arch/arm64/kernel/signal.c:setup_rt_frame",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:__arm64_sys_rt_sigreturn",
        "arch/arm64/kernel/signal.c:restore_sigframe",
        "arch/arm64/kernel/signal.c:restore_sigframe",
        "arch/arm64/kernel/signal.c:restore_sigframe",
        "arch/arm64/kernel/signal.c:restore_sigframe",
        "arch/arm64/kernel/signal.c:preserve_sve_context",
        "arch/arm64/kernel/signal.c:preserve_sve_context",
        "arch/arm64/kernel/signal.c:preserve_sve_context",
        "arch/arm64/kernel/signal.c:restore_fpsimd_context",
        "arch/arm64/kernel/signal.c:restore_fpsimd_context",
        "arch/arm64/kernel/signal.c:restore_fpsimd_context",
        "arch/arm64/kernel/signal.c:restore_fpsimd_context",
        "arch/arm64/kernel/signal.c:preserve_fpsimd_context",
        "arch/arm64/kernel/signal.c:preserve_fpsimd_context",
        "arch/arm64/kernel/signal.c:preserve_fpsimd_context",
        "arch/arm64/kernel/signal.c:preserve_fpsimd_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490238904,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/traps.c:call_undef_hook",
        "arch/arm64/kernel/traps.c:call_undef_hook",
        "arch/arm64/kernel/traps.c:call_undef_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490292152,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kernel/signal32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/signal32.c:compat_setup_frame",
        "arch/arm64/kernel/signal32.c:compat_setup_rt_frame",
        "arch/arm64/kernel/signal32.c:compat_setup_rt_frame",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:compat_setup_sigframe",
        "arch/arm64/kernel/signal32.c:__arm64_compat_sys_rt_sigreturn",
        "arch/arm64/kernel/signal32.c:__arm64_compat_sys_sigreturn",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_restore_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_restore_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_restore_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_restore_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_preserve_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_preserve_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_preserve_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_preserve_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_preserve_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_preserve_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_preserve_vfp_context",
        "arch/arm64/kernel/signal32.c:compat_preserve_vfp_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490292808,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kernel/sys_compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/sys_compat.c:compat_arm_syscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490301084,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kernel/perf_callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/perf_callchain.c:perf_callchain_user",
        "arch/arm64/kernel/perf_callchain.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490322968,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kernel/armv8_deprecated.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/armv8_deprecated.c:swp_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490334448,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kernel/crash_dump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/crash_dump.c:copy_oldmem_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490397424,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_get_dirty_log_protect",
        "virt/kvm/kvm_main.c:kvm_get_dirty_log",
        "virt/kvm/kvm_main.c:__kvm_set_memory_region",
        "virt/kvm/kvm_main.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490426504,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "virt/kvm/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/vfio.c:kvm_vfio_set_group",
        "virt/kvm/vfio.c:kvm_vfio_set_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490448680,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl",
        "virt/kvm/arm/arm.c:_copy_to_user",
        "virt/kvm/arm/arm.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490478948,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "virt/kvm/arm/psci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/psci.c:kvm_arm_set_fw_reg",
        "virt/kvm/arm/psci.c:kvm_arm_get_fw_reg",
        "virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices",
        "virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices",
        "virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490494996,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kvm/guest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/guest.c:kvm_arm_get_reg",
        "arch/arm64/kvm/guest.c:kvm_arm_get_reg",
        "arch/arm64/kvm/guest.c:kvm_arm_get_reg",
        "arch/arm64/kvm/guest.c:kvm_arm_get_reg",
        "arch/arm64/kvm/guest.c:kvm_arm_get_reg",
        "arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices",
        "arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices",
        "arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices",
        "arch/arm64/kvm/guest.c:copy_core_reg_indices",
        "arch/arm64/kvm/guest.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490524044,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "arch/arm64/kvm/sys_regs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/sys_regs.c:kvm_arm_copy_sys_reg_indices",
        "arch/arm64/kvm/sys_regs.c:kvm_arm_copy_sys_reg_indices",
        "arch/arm64/kvm/sys_regs.c:walk_one_sys_reg",
        "arch/arm64/kvm/sys_regs.c:kvm_arm_sys_reg_set_reg",
        "arch/arm64/kvm/sys_regs.c:kvm_arm_sys_reg_get_reg",
        "arch/arm64/kvm/sys_regs.c:reg_to_user",
        "arch/arm64/kvm/sys_regs.c:get_wcr",
        "arch/arm64/kvm/sys_regs.c:get_wvr",
        "arch/arm64/kvm/sys_regs.c:get_bcr",
        "arch/arm64/kvm/sys_regs.c:get_bvr",
        "arch/arm64/kvm/sys_regs.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490574300,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "virt/kvm/arm/vgic/vgic-kvm-device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_get_attr",
        "virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_set_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490588108,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "virt/kvm/arm/vgic/vgic-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490606976,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "virt/kvm/arm/arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arch_timer.c:kvm_arm_timer_get_attr",
        "virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490612488,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "virt/kvm/arm/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_get_attr",
        "virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_set_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490635852,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__arm64_sys_clone3",
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:mm_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490665744,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_compat_sys_waitid",
        "kernel/exit.c:__do_sys_wait4",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid",
        "kernel/exit.c:__do_sys_waitid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490691676,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_put_long",
        "kernel/sysctl.c:_proc_do_string",
        "kernel/sysctl.c:_proc_do_string",
        "kernel/sysctl.c:_proc_do_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490702156,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/sysctl_binary.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__arm64_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__arm64_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__arm64_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__arm64_sys_sysctl",
        "kernel/sysctl_binary.c:__arm64_sys_sysctl",
        "kernel/sysctl_binary.c:__arm64_sys_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490705748,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__arm64_sys_capset",
        "kernel/capability.c:__arm64_sys_capset",
        "kernel/capability.c:__arm64_sys_capget",
        "kernel/capability.c:__arm64_sys_capget",
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490719748,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:generic_ptrace_peekdata",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_get_syscall_info",
        "kernel/ptrace.c:ptrace_peek_siginfo",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490739048,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__arm64_sys_rt_sigsuspend",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__arm64_sys_rt_sigaction",
        "kernel/signal.c:__arm64_sys_sigprocmask",
        "kernel/signal.c:__arm64_sys_sigprocmask",
        "kernel/signal.c:__arm64_compat_sys_sigpending",
        "kernel/signal.c:__arm64_sys_sigpending",
        "kernel/signal.c:__compat_save_altstack",
        "kernel/signal.c:__compat_save_altstack",
        "kernel/signal.c:__compat_save_altstack",
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:__save_altstack",
        "kernel/signal.c:__save_altstack",
        "kernel/signal.c:__save_altstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__arm64_sys_sigaltstack",
        "kernel/signal.c:__arm64_sys_sigaltstack",
        "kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__arm64_sys_rt_sigtimedwait",
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:__copy_siginfo_from_user32",
        "kernel/signal.c:copy_siginfo_to_user32",
        "kernel/signal.c:copy_siginfo_from_user",
        "kernel/signal.c:__copy_siginfo_from_user",
        "kernel/signal.c:copy_siginfo_to_user",
        "kernel/signal.c:copy_siginfo_to_user",
        "kernel/signal.c:__arm64_compat_sys_rt_sigpending",
        "kernel/signal.c:__arm64_sys_rt_sigpending",
        "kernel/signal.c:__arm64_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__arm64_sys_rt_sigprocmask",
        "kernel/signal.c:set_user_sigmask"
      ],
      "caller_func": [
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigaction"
      ]
    },
    {
      "addr": 18446603336490776084,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_compat_sys_sysinfo",
        "kernel/sys.c:__do_sys_sysinfo",
        "kernel/sys.c:__arm64_sys_getcpu",
        "kernel/sys.c:__arm64_sys_getcpu",
        "kernel/sys.c:__arm64_sys_prctl",
        "kernel/sys.c:__arm64_sys_prctl",
        "kernel/sys.c:__arm64_sys_prctl",
        "kernel/sys.c:__arm64_sys_prctl",
        "kernel/sys.c:prctl_set_auxv",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:__do_sys_getrusage",
        "kernel/sys.c:__arm64_sys_setrlimit",
        "kernel/sys.c:__arm64_sys_prlimit64",
        "kernel/sys.c:__arm64_sys_prlimit64",
        "kernel/sys.c:__arm64_compat_sys_getrlimit",
        "kernel/sys.c:__arm64_compat_sys_setrlimit",
        "kernel/sys.c:__arm64_sys_getrlimit",
        "kernel/sys.c:__arm64_sys_setdomainname",
        "kernel/sys.c:__arm64_sys_gethostname",
        "kernel/sys.c:__arm64_sys_sethostname",
        "kernel/sys.c:__do_sys_newuname",
        "kernel/sys.c:__do_sys_newuname",
        "kernel/sys.c:__do_sys_newuname",
        "kernel/sys.c:__arm64_compat_sys_times",
        "kernel/sys.c:__arm64_sys_times",
        "kernel/sys.c:__arm64_sys_getresgid",
        "kernel/sys.c:__arm64_sys_getresgid",
        "kernel/sys.c:__arm64_sys_getresgid",
        "kernel/sys.c:__arm64_sys_getresuid",
        "kernel/sys.c:__arm64_sys_getresuid",
        "kernel/sys.c:__arm64_sys_getresuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490880892,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:groups_from_user",
        "kernel/groups.c:groups_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490928492,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__arm64_sys_sched_getaffinity",
        "kernel/sched/core.c:__arm64_sys_sched_getattr",
        "kernel/sched/core.c:__arm64_sys_sched_getattr",
        "kernel/sched/core.c:__arm64_sys_sched_getparam",
        "kernel/sched/core.c:__arm64_sys_sched_setattr",
        "kernel/sched/core.c:__arm64_sys_sched_setattr",
        "kernel/sched/core.c:schedule_tail",
        "kernel/sched/core.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491076556,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sched_feat_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491106532,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491128768,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:pm_qos_power_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491152816,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print",
        "kernel/printk/printk.c:devkmsg_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491301220,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:kcmp_epoll_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491308080,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491316064,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:put_old_itimerspec32",
        "kernel/time/time.c:put_old_itimerspec32",
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_itimerspec64",
        "kernel/time/time.c:put_old_timespec32",
        "kernel/time/time.c:put_old_timex32",
        "kernel/time/time.c:__do_sys_adjtimex",
        "kernel/time/time.c:__arm64_compat_sys_gettimeofday",
        "kernel/time/time.c:__arm64_compat_sys_gettimeofday",
        "kernel/time/time.c:__arm64_compat_sys_gettimeofday",
        "kernel/time/time.c:__arm64_sys_gettimeofday",
        "kernel/time/time.c:__arm64_sys_gettimeofday",
        "kernel/time/time.c:__arm64_sys_gettimeofday",
        "kernel/time/time.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491387996,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-timers.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491401288,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__arm64_sys_setitimer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491430572,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:__arm64_compat_sys_get_robust_list",
        "kernel/futex.c:__arm64_compat_sys_get_robust_list",
        "kernel/futex.c:compat_fetch_robust_entry",
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:futex_cleanup",
        "kernel/futex.c:fetch_robust_entry",
        "kernel/futex.c:handle_futex_death",
        "kernel/futex.c:__arm64_sys_get_robust_list",
        "kernel/futex.c:__arm64_sys_get_robust_list",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491458928,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/uid16.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:__arm64_sys_setgroups16",
        "kernel/uid16.c:__arm64_sys_getgroups16",
        "kernel/uid16.c:__arm64_sys_getresgid16",
        "kernel/uid16.c:__arm64_sys_getresgid16",
        "kernel/uid16.c:__arm64_sys_getresgid16",
        "kernel/uid16.c:__arm64_sys_getresuid16",
        "kernel/uid16.c:__arm64_sys_getresuid16",
        "kernel/uid16.c:__arm64_sys_getresuid16"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491471696,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:copy_chunked_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491502424,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491508968,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec.c:__arm64_compat_sys_kexec_load",
        "kernel/kexec.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491513844,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_alloc_user_space",
        "kernel/compat.c:get_compat_sigset",
        "kernel/compat.c:compat_put_bitmap",
        "kernel/compat.c:compat_put_bitmap",
        "kernel/compat.c:compat_put_bitmap",
        "kernel/compat.c:compat_put_bitmap",
        "kernel/compat.c:compat_get_bitmap",
        "kernel/compat.c:compat_get_bitmap",
        "kernel/compat.c:compat_get_bitmap",
        "kernel/compat.c:compat_get_bitmap",
        "kernel/compat.c:get_compat_sigevent",
        "kernel/compat.c:get_compat_sigevent",
        "kernel/compat.c:get_compat_sigevent",
        "kernel/compat.c:get_compat_sigevent",
        "kernel/compat.c:get_compat_sigevent",
        "kernel/compat.c:put_compat_rusage",
        "kernel/compat.c:__arm64_compat_sys_sigprocmask",
        "kernel/compat.c:__arm64_compat_sys_sigprocmask",
        "kernel/compat.c:put_compat_itimerval",
        "kernel/compat.c:get_compat_itimerval",
        "kernel/compat.c:compat_put_timespec",
        "kernel/compat.c:compat_put_timespec",
        "kernel/compat.c:compat_put_timespec",
        "kernel/compat.c:compat_get_timespec",
        "kernel/compat.c:compat_get_timespec",
        "kernel/compat.c:compat_get_timespec",
        "kernel/compat.c:compat_put_timeval",
        "kernel/compat.c:compat_put_timeval",
        "kernel/compat.c:compat_put_timeval",
        "kernel/compat.c:compat_get_timeval",
        "kernel/compat.c:compat_get_timeval",
        "kernel/compat.c:compat_get_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491625796,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:proc_setgroups_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491696248,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:write_enabled_file_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491771236,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/seccomp.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491778840,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_file_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491889532,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_buffers_read",
        "kernel/trace/trace.c:trace_get_user",
        "kernel/trace/trace.c:trace_get_user",
        "kernel/trace/trace.c:trace_get_user",
        "kernel/trace/trace.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491952644,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492050796,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:perf_event_query_prog_array",
        "kernel/trace/bpf_trace.c:_copy_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492094960,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492118300,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492142244,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492160288,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:bpf_verifier_vlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492277108,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_get_info_by_fd",
        "kernel/bpf/btf.c:btf_get_info_by_fd",
        "kernel/bpf/btf.c:btf_get_info_by_fd",
        "kernel/bpf/btf.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492297876,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_prog_offload_info_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492311548,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query",
        "kernel/bpf/cgroup.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492353420,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_copy_attr",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:_copy_from_user"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_copy_attr"
      ]
    },
    {
      "addr": 18446603336492407088,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:is_trap_at_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492434316,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__arm64_sys_rseq",
        "kernel/rseq.c:__arm64_sys_rseq",
        "kernel/rseq.c:__arm64_sys_rseq",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume",
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492489856,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492594104,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492614768,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492725444,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492761584,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492765480,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore",
        "mm/mincore.c:__do_sys_mincore",
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493006700,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__arm64_compat_sys_migrate_pages",
        "mm/mempolicy.c:__arm64_compat_sys_migrate_pages",
        "mm/mempolicy.c:__arm64_compat_sys_mbind",
        "mm/mempolicy.c:__arm64_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__arm64_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__arm64_compat_sys_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:get_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493115460,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__arm64_compat_sys_move_pages",
        "mm/migrate.c:__arm64_compat_sys_move_pages",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:store_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493268496,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493285860,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__arm64_sys_memfd_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493316624,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__arm64_sys_copy_file_range",
        "fs/read_write.c:__arm64_sys_copy_file_range",
        "fs/read_write.c:__arm64_sys_copy_file_range",
        "fs/read_write.c:__arm64_sys_copy_file_range",
        "fs/read_write.c:__arm64_compat_sys_sendfile64",
        "fs/read_write.c:__arm64_compat_sys_sendfile64",
        "fs/read_write.c:__arm64_compat_sys_sendfile",
        "fs/read_write.c:__arm64_compat_sys_sendfile",
        "fs/read_write.c:__arm64_sys_sendfile64",
        "fs/read_write.c:__arm64_sys_sendfile64",
        "fs/read_write.c:__arm64_sys_sendfile",
        "fs/read_write.c:__arm64_sys_sendfile",
        "fs/read_write.c:compat_rw_copy_check_uvector",
        "fs/read_write.c:compat_rw_copy_check_uvector",
        "fs/read_write.c:compat_rw_copy_check_uvector",
        "fs/read_write.c:compat_rw_copy_check_uvector",
        "fs/read_write.c:rw_copy_check_uvector",
        "fs/read_write.c:__arm64_sys_llseek"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493346172,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:cp_compat_stat",
        "fs/stat.c:cp_statx",
        "fs/stat.c:cp_new_stat64",
        "fs/stat.c:cp_new_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493356504,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493372580,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:pipe_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493411588,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:readlink_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493418372,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493425900,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:ioctl_preallocate",
        "fs/ioctl.c:fiemap_fill_next_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493431652,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:__arm64_compat_sys_getdents",
        "fs/readdir.c:__arm64_compat_sys_getdents",
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:ksys_getdents64",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:__arm64_sys_getdents",
        "fs/readdir.c:__arm64_sys_getdents",
        "fs/readdir.c:filldir",
        "fs/readdir.c:filldir",
        "fs/readdir.c:filldir",
        "fs/readdir.c:filldir",
        "fs/readdir.c:filldir",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493449344,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:__arm64_compat_sys_pselect6_time32",
        "fs/select.c:__arm64_compat_sys_pselect6_time32",
        "fs/select.c:__arm64_compat_sys_pselect6_time32",
        "fs/select.c:__arm64_compat_sys_pselect6_time64",
        "fs/select.c:__arm64_compat_sys_pselect6_time64",
        "fs/select.c:__arm64_compat_sys_pselect6_time64",
        "fs/select.c:__arm64_compat_sys_old_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:__arm64_sys_pselect6",
        "fs/select.c:__arm64_sys_pselect6",
        "fs/select.c:__arm64_sys_pselect6",
        "fs/select.c:__arm64_sys_select",
        "fs/select.c:poll_select_finish",
        "fs/select.c:poll_select_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493511652,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:fs_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493516824,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:exact_copy_from_user",
        "fs/namespace.c:exact_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493550924,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493558048,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/xattr.c:listxattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493570860,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_read_from_buffer",
        "fs/libfs.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493625224,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:do_splice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493633424,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/utimes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__arm64_sys_utime32",
        "fs/utimes.c:__arm64_sys_utime32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493637340,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__arm64_sys_getcwd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493642368,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/statfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:put_compat_statfs64",
        "fs/statfs.c:put_compat_statfs",
        "fs/statfs.c:__do_sys_ustat",
        "fs/statfs.c:do_statfs64",
        "fs/statfs.c:do_statfs_native"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493648120,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/nsfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:ns_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493658948,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:fscontext_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493747080,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_ioctl",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read",
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493757588,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_ioctl",
        "fs/notify/fanotify/fanotify_user.c:fanotify_write",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493771512,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:ep_send_events_proc",
        "fs/eventpoll.c:ep_send_events_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493775888,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_copyinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493781700,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:timerfd_ioctl",
        "fs/timerfd.c:timerfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493785812,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493795672,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493812852,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__arm64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__arm64_compat_sys_io_pgetevents",
        "fs/aio.c:__arm64_sys_io_pgetevents",
        "fs/aio.c:__arm64_sys_io_cancel",
        "fs/aio.c:__arm64_compat_sys_io_submit",
        "fs/aio.c:__arm64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:__arm64_compat_sys_io_setup",
        "fs/aio.c:__arm64_compat_sys_io_setup",
        "fs/aio.c:__arm64_sys_io_setup",
        "fs/aio.c:__arm64_sys_io_setup",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493842280,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_setup",
        "fs/io_uring.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493883972,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/crypto/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493893772,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/crypto/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex",
        "fs/crypto/policy.c:fscrypt_ioctl_get_policy",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/crypto/policy.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493896688,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493900728,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/verity/measure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/measure.c:fsverity_ioctl_measure",
        "fs/verity/measure.c:fsverity_ioctl_measure",
        "fs/verity/measure.c:fsverity_ioctl_measure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493946056,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans",
        "fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans",
        "fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans",
        "fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans",
        "fs/compat_ioctl.c:sg_grt_trans",
        "fs/compat_ioctl.c:sg_grt_trans",
        "fs/compat_ioctl.c:sg_grt_trans",
        "fs/compat_ioctl.c:sg_grt_trans",
        "fs/compat_ioctl.c:sg_grt_trans",
        "fs/compat_ioctl.c:sg_grt_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_build_iovec",
        "fs/compat_ioctl.c:sg_build_iovec",
        "fs/compat_ioctl.c:sg_build_iovec",
        "fs/compat_ioctl.c:sg_build_iovec",
        "fs/compat_ioctl.c:sg_build_iovec"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans"
      ]
    },
    {
      "addr": 18446603336493961556,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446603336493976064,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:fill_psinfo",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493996232,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:__arm64_sys_name_to_handle_at",
        "fs/fhandle.c:__arm64_sys_name_to_handle_at",
        "fs/fhandle.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494050548,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:do_quotactl",
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota",
        "fs/quota/quota.c:quota_getxstatev",
        "fs/quota/quota.c:quota_getnextquota",
        "fs/quota/quota.c:quota_getquota",
        "fs/quota/quota.c:quota_getinfo",
        "fs/quota/quota.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494065556,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494091124,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494146824,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:_copy_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494148352,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494152432,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494175416,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_write",
        "fs/kernfs/file.c:kernfs_fop_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494192092,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/configfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/file.c:configfs_write_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494216368,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/dcookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcookies.c:do_lookup_dcookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494404540,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_compat_ioctl",
        "fs/ext4/ioctl.c:ext4_compat_ioctl",
        "fs/ext4/ioctl.c:ext4_compat_ioctl",
        "fs/ext4/ioctl.c:ext4_compat_ioctl",
        "fs/ext4/ioctl.c:ext4_compat_ioctl",
        "fs/ext4/ioctl.c:ext4_compat_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_getfsmap_format",
        "fs/ext4/ioctl.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494770460,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_compat_dir_ioctl",
        "fs/fat/dir.c:fat_compat_dir_ioctl",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_compat_ioctl_filldir",
        "fs/fat/dir.c:fat_dir_ioctl",
        "fs/fat/dir.c:fat_dir_ioctl",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir",
        "fs/fat/dir.c:fat_ioctl_filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494789176,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/file.c:fat_generic_ioctl",
        "fs/fat/file.c:fat_ioctl_set_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494866508,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/ecryptfs/miscdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494881460,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494987920,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "fs/efivarfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494991088,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "ipc/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/compat.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494998136,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "ipc/msgutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msgutil.c:_copy_to_user",
        "ipc/msgutil.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495001724,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:compat_do_msg_fill",
        "ipc/msg.c:do_msg_fill",
        "ipc/msg.c:compat_ksys_msgsnd",
        "ipc/msg.c:ksys_msgsnd",
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/msg.c:copy_compat_msqid_to_user",
        "ipc/msg.c:copy_compat_msqid_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495014564,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:copy_compat_semid_to_user",
        "ipc/sem.c:copy_compat_semid_to_user",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495039224,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:compat_ksys_shmctl",
        "ipc/shm.c:compat_ksys_shmctl",
        "ipc/shm.c:compat_ksys_shmctl",
        "ipc/shm.c:copy_compat_shmid_to_user",
        "ipc/shm.c:copy_compat_shmid_to_user",
        "ipc/shm.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495050004,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495072208,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:keyring_read_iterator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495079240,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:_copy_to_user",
        "security/keys/keyctl.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495096884,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495098980,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/keys/user_defined.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/user_defined.c:user_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495100080,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/keys/compat_dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495105340,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:keyctl_dh_compute_kdf",
        "security/keys/dh.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495109132,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/keys/keyctl_pkey.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_query",
        "security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495112128,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495117544,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:trusted_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495125264,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/encrypted-keys/encrypted.c:_copy_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495200892,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream",
        "security/selinux/hooks.c:selinux_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495229636,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495337748,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_socket_getpeersec_stream",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495358760,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/smack/smackfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smackfs.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495387184,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_flush",
        "security/tomoyo/common.c:tomoyo_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495425612,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_read_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495443528,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495523232,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495891580,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "block/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:blkdev_ioctl",
        "block/ioctl.c:put_uint",
        "block/ioctl.c:put_int",
        "block/ioctl.c:put_ushort",
        "block/ioctl.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495960148,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "block/scsi_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/scsi_ioctl.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495964944,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_ioctl",
        "block/bsg.c:bsg_ioctl",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_scsi_complete_rq",
        "block/bsg.c:bsg_scsi_fill_hdr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495968876,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "block/bsg-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_transport_complete_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496038156,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkpg_ioctl",
        "block/compat_ioctl.c:compat_blkpg_ioctl",
        "block/compat_ioctl.c:compat_blkpg_ioctl",
        "block/compat_ioctl.c:compat_blkpg_ioctl",
        "block/compat_ioctl.c:compat_blkpg_ioctl",
        "block/compat_ioctl.c:compat_blkpg_ioctl",
        "block/compat_ioctl.c:compat_blkpg_ioctl",
        "block/compat_ioctl.c:compat_blkpg_ioctl",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_put_uint",
        "block/compat_ioctl.c:compat_put_int",
        "block/compat_ioctl.c:compat_put_ushort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496053104,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:_copy_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496069516,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "block/blk-mq-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:queue_state_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496088712,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "block/sed-opal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:write_shadow_mbr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496101744,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse_user",
        "lib/bitmap.c:__bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496111600,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:import_single_range",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copyin",
        "lib/iov_iter.c:copyout",
        "lib/iov_iter.c:fault_in_pages_readable",
        "lib/iov_iter.c:fault_in_pages_readable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496138484,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kfifo.c:kfifo_copy_to_user",
        "lib/kfifo.c:kfifo_copy_to_user",
        "lib/kfifo.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496152144,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/usercopy.c:check_zeroed_user",
        "lib/usercopy.c:check_zeroed_user",
        "lib/usercopy.c:check_zeroed_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496159504,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496344272,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "lib/strncpy_from_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/strncpy_from_user.c:strncpy_from_user",
        "lib/strncpy_from_user.c:do_strncpy_from_user",
        "lib/strncpy_from_user.c:do_strncpy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496345236,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "lib/strnlen_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/strnlen_user.c:strnlen_user",
        "lib/strnlen_user.c:do_strnlen_user",
        "lib/strnlen_user.c:do_strnlen_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496722300,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_ioctl",
        "drivers/gpio/gpiolib.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496932584,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_write",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_read",
        "drivers/pci/proc.c:proc_bus_pci_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497073464,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/pci/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_write",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_write",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_write",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_read",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_read",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_read",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_read",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_read",
        "drivers/pci/syscall.c:__arm64_sys_pciconfig_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497252340,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:do_fb_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/video/fbdev/core/fbmem.c:fb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497270256,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcmap.c:_copy_to_user",
        "drivers/video/fbdev/core/fbcmap.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497311888,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497342604,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_ioctl",
        "drivers/video/fbdev/imsttfb.c:imsttfb_ioctl",
        "drivers/video/fbdev/imsttfb.c:imsttfb_ioctl",
        "drivers/video/fbdev/imsttfb.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498260052,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498355756,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:compat_tty_tiocgserial",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498371500,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_ioctl",
        "drivers/tty/n_tty.c:n_tty_ioctl",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:copy_from_read_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498394252,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_mode_ioctl",
        "drivers/tty/tty_ioctl.c:tty_mode_ioctl",
        "drivers/tty/tty_ioctl.c:tty_mode_ioctl",
        "drivers/tty/tty_ioctl.c:tty_mode_ioctl",
        "drivers/tty/tty_ioctl.c:tty_mode_ioctl",
        "drivers/tty/tty_ioctl.c:tty_mode_ioctl",
        "drivers/tty/tty_ioctl.c:set_termiox",
        "drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio",
        "drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio",
        "drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio",
        "drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio",
        "drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio",
        "drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio",
        "drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios",
        "drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios",
        "drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios",
        "drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios",
        "drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios",
        "drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498416072,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498421288,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_get_pktmode",
        "drivers/tty/pty.c:pty_set_pktmode",
        "drivers/tty/pty.c:pty_get_lock",
        "drivers/tty/pty.c:pty_set_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498432824,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:write_sysrq_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498442380,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl",
        "drivers/tty/vt/vt_ioctl.c:_copy_from_user"
      ],
      "caller_func": [
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl"
      ]
    },
    {
      "addr": 18446603336498445500,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/vt/vc_screen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vc_screen.c:vcs_write",
        "drivers/tty/vt/vc_screen.c:vcs_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498451400,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498473568,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:vt_do_kdskled",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498479360,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/vt/consolemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_get_unimap",
        "drivers/tty/vt/consolemap.c:con_get_trans_new",
        "drivers/tty/vt/consolemap.c:con_get_trans_old",
        "drivers/tty/vt/consolemap.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498515896,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/tty/vt/vt.c:con_get_cmap",
        "drivers/tty/vt/vt.c:con_set_cmap",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux",
        "drivers/tty/vt/vt.c:tioclinux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498555132,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:uart_ioctl",
        "drivers/tty/serial/serial_core.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498720960,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_port",
        "drivers/char/mem.c:write_port",
        "drivers/char/mem.c:read_port",
        "drivers/char/mem.c:read_port",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498745480,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498764840,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498772016,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498777220,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_write",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498937808,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499178212,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/base/regmap/regmap-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499216860,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_info64_to_compat",
        "drivers/block/loop.c:loop_get_status64",
        "drivers/block/loop.c:loop_get_status_old",
        "drivers/block/loop.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499241216,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499373276,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_get_set_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499382012,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_reg_write_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499402952,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:_copy_to_user",
        "drivers/nvdimm/bus.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499486976,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499504736,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:_copy_to_user",
        "drivers/dma-buf/sync_file.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499509892,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499514760,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499528204,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499547300,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_error.c:scsi_ioctl_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499596332,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/scsi/scsi_devinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499598520,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/scsi/scsi_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_proc.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499675660,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_new_read",
        "drivers/scsi/sg.c:sg_new_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499745976,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl",
        "drivers/ata/libata-scsi.c:ata_task_ioctl",
        "drivers/ata/libata-scsi.c:ata_cmd_ioctl",
        "drivers/ata/libata-scsi.c:_copy_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499856768,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_write",
        "drivers/gpu/vga/vgaarb.c:vga_arb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499984492,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:_copy_to_user",
        "drivers/net/tun.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500039976,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/net/ethernet/freescale/fec_ptp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500120592,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/net/ppp/ppp_generic.c:ppp_set_compress",
        "drivers/net/ppp/ppp_generic.c:ppp_net_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_net_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_net_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/net/ppp/ppp_generic.c:ppp_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500179052,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:cdrom_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old",
        "drivers/cdrom/cdrom.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500316152,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:processcompl_compat",
        "drivers/usb/core/devio.c:processcompl_compat",
        "drivers/usb/core/devio.c:processcompl_compat",
        "drivers/usb/core/devio.c:processcompl_compat",
        "drivers/usb/core/devio.c:processcompl_compat",
        "drivers/usb/core/devio.c:processcompl_compat",
        "drivers/usb/core/devio.c:get_urb32",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "drivers/usb/core/devio.c:processcompl",
        "drivers/usb/core/devio.c:processcompl",
        "drivers/usb/core/devio.c:processcompl",
        "drivers/usb/core/devio.c:processcompl",
        "drivers/usb/core/devio.c:processcompl",
        "drivers/usb/core/devio.c:processcompl",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:copy_urb_data_to_user",
        "drivers/usb/core/devio.c:copy_urb_data_to_user",
        "drivers/usb/core/devio.c:usbdev_read",
        "drivers/usb/core/devio.c:usbdev_read"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control"
      ]
    },
    {
      "addr": 18446603336500333544,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/usb/core/devices.c:usb_device_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500706564,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500744968,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/input/input-compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input-compat.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500758580,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_read",
        "drivers/input/mousedev.c:mousedev_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500772020,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_handle_set_keycode_v2",
        "drivers/input/evdev.c:evdev_handle_set_keycode",
        "drivers/input/evdev.c:evdev_handle_get_keycode_v2",
        "drivers/input/evdev.c:evdev_handle_get_keycode",
        "drivers/input/evdev.c:str_to_user",
        "drivers/input/evdev.c:bits_to_user"
      ],
      "caller_func": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl"
      ]
    },
    {
      "addr": 18446603336500793588,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/input/misc/uinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/misc/uinput.c:uinput_str_to_user",
        "drivers/input/misc/uinput.c:uinput_str_to_user",
        "drivers/input/misc/uinput.c:uinput_ff_upload_to_user",
        "drivers/input/misc/uinput.c:uinput_ff_upload_to_user",
        "drivers/input/misc/uinput.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500817428,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/rtc/dev.c:rtc_dev_read",
        "drivers/rtc/dev.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500873184,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_read",
        "drivers/i2c/i2c-dev.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500914548,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-api.c:cec_ioctl",
        "drivers/media/cec/cec-api.c:cec_ioctl",
        "drivers/media/cec/cec-api.c:cec_ioctl",
        "drivers/media/cec/cec-api.c:cec_ioctl",
        "drivers/media/cec/cec-api.c:cec_ioctl",
        "drivers/media/cec/cec-api.c:cec_ioctl",
        "drivers/media/cec/cec-api.c:cec_ioctl",
        "drivers/media/cec/cec-api.c:cec_ioctl",
        "drivers/media/cec/cec-api.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500928148,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/pps/pps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pps/pps.c:pps_cdev_ioctl",
        "drivers/pps/pps.c:_copy_to_user",
        "drivers/pps/pps.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500934960,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/ptp/ptp_chardev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_chardev.c:_copy_to_user",
        "drivers/ptp/ptp_chardev.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501036888,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501114280,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:_copy_from_user"
      ],
      "caller_func": [
        "drivers/md/md.c:md_ioctl"
      ]
    },
    {
      "addr": 18446603336501203396,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:ctl_ioctl",
        "drivers/md/dm-ioctl.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501262460,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/edac/altera_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/altera_edac.c:altr_edac_a10_device_trig2",
        "drivers/edac/altera_edac.c:altr_edac_a10_device_trig",
        "drivers/edac/altera_edac.c:altr_edac_device_trig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501436776,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501700384,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "drivers/remoteproc/remoteproc_debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501849440,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_sioc_ifmap",
        "net/socket.c:compat_ifr_data_ioctl",
        "net/socket.c:compat_ifr_data_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:do_recvmmsg",
        "net/socket.c:do_recvmmsg",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:__sys_sendmmsg",
        "net/socket.c:copy_msghdr_from_user",
        "net/socket.c:__arm64_sys_getsockopt",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_do_ioctl",
        "net/socket.c:sock_do_ioctl",
        "net/socket.c:sock_do_ioctl",
        "net/socket.c:sock_do_ioctl",
        "net/socket.c:move_addr_to_user",
        "net/socket.c:move_addr_to_user",
        "net/socket.c:move_addr_to_user"
      ],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ]
    },
    {
      "addr": 18446603336501882968,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:groups_to_user",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501945452,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:scm_detach_fds",
        "net/core/scm.c:put_cmsg",
        "net/core/scm.c:put_cmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501965312,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501975704,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502069496,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:ethtool_get_per_queue_coalesce",
        "net/core/ethtool.c:ethtool_get_value",
        "net/core/ethtool.c:ethtool_get_channels",
        "net/core/ethtool.c:ethtool_get_coalesce",
        "net/core/ethtool.c:ethtool_get_any_eeprom",
        "net/core/ethtool.c:ethtool_get_any_eeprom",
        "net/core/ethtool.c:ethtool_set_rxfh",
        "net/core/ethtool.c:ethtool_get_rxfh",
        "net/core/ethtool.c:ethtool_get_rxfh",
        "net/core/ethtool.c:ethtool_get_rxfh",
        "net/core/ethtool.c:ethtool_get_rxfh_indir",
        "net/core/ethtool.c:ethtool_get_rxfh_indir",
        "net/core/ethtool.c:ethtool_get_rxnfc",
        "net/core/ethtool.c:ethtool_get_rxnfc",
        "net/core/ethtool.c:ethtool_set_rxnfc",
        "net/core/ethtool.c:ethtool_get_sset_info",
        "net/core/ethtool.c:ethtool_get_sset_info",
        "net/core/ethtool.c:ethtool_get_drvinfo",
        "net/core/ethtool.c:ethtool_get_settings",
        "net/core/ethtool.c:ethtool_get_link_ksettings",
        "net/core/ethtool.c:ethtool_get_features",
        "net/core/ethtool.c:ethtool_get_features",
        "net/core/ethtool.c:ethtool_get_features",
        "net/core/ethtool.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502226992,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_get_filter",
        "net/core/filter.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502230808,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/core/dev_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502423256,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:__do_compat_sys_socketcall",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog",
        "net/compat.c:get_compat_bpf_fprog",
        "net/compat.c:scm_detach_fds_compat",
        "net/compat.c:scm_detach_fds_compat",
        "net/compat.c:scm_detach_fds_compat",
        "net/compat.c:scm_detach_fds_compat",
        "net/compat.c:put_cmsg_compat",
        "net/compat.c:put_cmsg_compat",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/compat.c:cmsghdr_from_user_compat_to_kern",
        "net/compat.c:get_compat_msghdr"
      ],
      "caller_func": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ]
    },
    {
      "addr": 18446603336502531992,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_setsockopt"
      ],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt"
      ]
    },
    {
      "addr": 18446603336502553488,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502613856,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_get_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502638020,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502673320,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_repair_options_est",
        "net/ipv4/tcp.c:tcp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502785692,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502833800,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_ioctl",
        "net/ipv4/raw.c:raw_ioctl",
        "net/ipv4/raw.c:raw_geticmpfilter",
        "net/ipv4/raw.c:raw_geticmpfilter",
        "net/ipv4/raw.c:raw_geticmpfilter",
        "net/ipv4/raw.c:raw_seticmpfilter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502846844,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_getsockopt",
        "net/ipv4/udp.c:udp_lib_getsockopt",
        "net/ipv4/udp.c:udp_lib_getsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_ioctl",
        "net/ipv4/udp.c:udp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502882328,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_ioctl",
        "net/ipv4/arp.c:arp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502896608,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_gifconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502918472,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502945848,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_gsfget",
        "net/ipv4/igmp.c:ip_mc_gsfget",
        "net/ipv4/igmp.c:ip_mc_msfget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502952000,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503026528,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503064200,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv4/ipmr.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503197840,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503263552,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503355968,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ipv6_route_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503378960,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503431752,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_ioctl",
        "net/ipv6/raw.c:rawv6_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503467952,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ip6_mc_msfget",
        "net/ipv6/mcast.c:_copy_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503487812,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503519704,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503556168,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503636036,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_ioctl",
        "net/packet/af_packet.c:packet_ioctl",
        "net/packet/af_packet.c:packet_getsockopt",
        "net/packet/af_packet.c:packet_getsockopt",
        "net/packet/af_packet.c:packet_getsockopt",
        "net/packet/af_packet.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503663860,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:compat_wext_handle_ioctl",
        "net/wireless/wext-core.c:wext_handle_ioctl",
        "net/wireless/wext-core.c:ioctl_standard_iw_point",
        "net/wireless/wext-core.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503666400,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/wireless/wext-priv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-priv.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503709468,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_write",
        "net/rfkill/core.c:rfkill_fop_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503785980,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_getsockopt",
        "net/xdp/xsk.c:xsk_getsockopt",
        "net/xdp/xsk.c:xsk_getsockopt",
        "net/xdp/xsk.c:xsk_getsockopt",
        "net/xdp/xsk.c:xsk_getsockopt",
        "net/xdp/xsk.c:xsk_getsockopt",
        "net/xdp/xsk.c:xsk_getsockopt",
        "net/xdp/xsk.c:_copy_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503853020,
      "name": "__range_ok",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:61",
      "file": "lib/seq_buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/seq_buf.c:seq_buf_to_user"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490196016,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336490723064,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336492120400,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336492321600,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336493932616,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336493947872,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336498433872,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336500297144,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336500761016,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336501042144,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336501823896,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336502420952,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336502519184,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336502667784,
      "name": "__range_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
long unsigned int __range_ok(const void * addr, long unsigned int size)
```
</details>
</li>
</ul>

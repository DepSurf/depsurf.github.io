# Function: <code>system_supports_sve</code>

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
bool system_supports_sve()
```

```json
{
  "name": "system_supports_sve",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490190876,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end",
        "arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin",
        "arch/arm64/kernel/fpsimd.c:fpsimd_update_current_state",
        "arch/arm64/kernel/fpsimd.c:fpsimd_bind_task_to_cpu",
        "arch/arm64/kernel/fpsimd.c:fpsimd_signal_preserve_current_state",
        "arch/arm64/kernel/fpsimd.c:fpsimd_flush_thread",
        "arch/arm64/kernel/fpsimd.c:do_sve_acc",
        "arch/arm64/kernel/fpsimd.c:sve_get_current_vl",
        "arch/arm64/kernel/fpsimd.c:sve_set_current_vl",
        "arch/arm64/kernel/fpsimd.c:sve_to_fpsimd",
        "arch/arm64/kernel/fpsimd.c:fpsimd_to_sve",
        "arch/arm64/kernel/fpsimd.c:fpsimd_save",
        "arch/arm64/kernel/fpsimd.c:task_fpsimd_load"
      ],
      "caller_func": [
        "arch/arm64/kernel/fpsimd.c:fpsimd_init",
        "arch/arm64/kernel/fpsimd.c:sve_setup"
      ]
    },
    {
      "addr": 18446603336490209976,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:sve_set",
        "arch/arm64/kernel/ptrace.c:sve_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490226376,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "arch/arm64/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/signal.c:setup_sigframe",
        "arch/arm64/kernel/signal.c:restore_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490266184,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "arch/arm64/kernel/cpufeature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpufeature.c:check_local_cpu_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490277616,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "arch/arm64/kernel/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/syscall.c:el0_svc_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490450648,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490497808,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "arch/arm64/kvm/guest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/guest.c:kvm_arm_set_reg",
        "arch/arm64/kvm/guest.c:kvm_arm_get_reg",
        "arch/arm64/kvm/guest.c:kvm_arm_num_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490503392,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "arch/arm64/kvm/reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/reset.c:kvm_reset_vcpu",
        "arch/arm64/kvm/reset.c:kvm_reset_vcpu",
        "arch/arm64/kvm/reset.c:kvm_arm_vcpu_is_finalized",
        "arch/arm64/kvm/reset.c:kvm_arm_vcpu_finalize",
        "arch/arm64/kvm/reset.c:kvm_arm_init_sve",
        "arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490517624,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "arch/arm64/kvm/sys_regs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/sys_regs.c:set_id_aa64zfr0_el1",
        "arch/arm64/kvm/sys_regs.c:get_id_aa64zfr0_el1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490528068,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "arch/arm64/kvm/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp",
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp",
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503977880,
      "name": "system_supports_sve",
      "external": false,
      "loc": "arch/arm64/include/asm/cpufeature.h:578",
      "file": "arch/arm64/kvm/hyp/switch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/hyp/switch.c:fixup_guest_exit",
        "arch/arm64/kvm/hyp/switch.c:fixup_guest_exit",
        "arch/arm64/kvm/hyp/switch.c:activate_traps_vhe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490184664,
      "name": "system_supports_sve",
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
bool system_supports_sve()
```
</details>
</li>
</ul>

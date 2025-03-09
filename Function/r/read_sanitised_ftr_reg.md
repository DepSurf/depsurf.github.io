# Function: <code>read_sanitised_ftr_reg</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u64 read_sanitised_ftr_reg(u32 id)
```

```json
{
  "name": "read_sanitised_ftr_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490263528,
      "name": "read_sanitised_ftr_reg",
      "external": true,
      "loc": "arch/arm64/kernel/cpufeature.c:800",
      "file": "arch/arm64/kernel/cpufeature.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/debug-monitors.c:debug_monitors_arch",
        "arch/arm64/kernel/fpsimd.c:sve_setup",
        "arch/arm64/kernel/cpufeature.c:check_local_cpu_capabilities",
        "arch/arm64/kernel/cpufeature.c:compat_has_neon",
        "arch/arm64/kernel/cpufeature.c:has_no_fpsimd",
        "arch/arm64/kernel/cpufeature.c:has_cpuid_feature",
        "arch/arm64/kernel/cpufeature.c:update_cpu_features",
        "arch/arm64/kernel/cpufeature.c:update_cpu_features",
        "arch/arm64/kernel/alternative.c:__apply_alternatives",
        "arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init",
        "arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init",
        "arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_slots",
        "arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_slots",
        "arch/arm64/kernel/armv8_deprecated.c:armv8_deprecated_init",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "arch/arm64/kvm/debug.c:kvm_arm_clear_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_clear_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/reset.c:kvm_arm_setup_stage2",
        "arch/arm64/kvm/reset.c:kvm_arm_setup_stage2",
        "arch/arm64/kvm/reset.c:kvm_set_ipa_limit",
        "arch/arm64/kvm/reset.c:kvm_reset_vcpu",
        "arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension",
        "arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension",
        "arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension",
        "arch/arm64/kvm/sys_regs.c:get_ctr_el0",
        "arch/arm64/kvm/sys_regs.c:trap_loregion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490263528,
      "name": "read_sanitised_ftr_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
u64 read_sanitised_ftr_reg(u32 id)
```
</details>
</li>
</ul>

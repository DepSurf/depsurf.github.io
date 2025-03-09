# Function: <code>has_vhe</code>

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
bool has_vhe()
```

```json
{
  "name": "has_vhe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490306284,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "arch/arm64/kernel/perf_event.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/perf_event.c:armv8pmu_disable_event",
        "arch/arm64/kernel/perf_event.c:armv8pmu_enable_event",
        "arch/arm64/kernel/perf_event.c:armv8pmu_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490441488,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:cpu_hyp_reinit",
        "virt/kvm/arm/arm.c:cpu_hyp_reinit",
        "virt/kvm/arm/arm.c:cpu_hyp_reinit",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_load",
        "virt/kvm/arm/arm.c:kvm_arch_free_vm",
        "virt/kvm/arm/arm.c:kvm_arch_alloc_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490451948,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490481996,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "arch/arm64/kvm/va_layout.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/va_layout.c:kvm_patch_vector_branch"
      ],
      "caller_func": [
        "arch/arm64/kvm/va_layout.c:kvm_update_va_mask",
        "arch/arm64/kvm/va_layout.c:kvm_update_va_mask"
      ]
    },
    {
      "addr": 18446603336490499868,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "arch/arm64/kvm/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_init_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490503056,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "arch/arm64/kvm/reset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/reset.c:kvm_reset_vcpu",
        "arch/arm64/kvm/reset.c:kvm_reset_vcpu",
        "arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490529712,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "arch/arm64/kvm/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/pmu.c:kvm_vcpu_pmu_restore_host",
        "arch/arm64/kvm/pmu.c:kvm_vcpu_pmu_restore_guest",
        "arch/arm64/kvm/pmu.c:kvm_set_pmu_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490537280,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "virt/kvm/arm/vgic/vgic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490541856,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "virt/kvm/arm/vgic/vgic-init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_init_cpu_hardware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490550912,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "virt/kvm/arm/vgic/vgic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_put",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_put",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_vmcr_sync",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490605280,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "virt/kvm/arm/arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init",
        "virt/kvm/arm/arch_timer.c:set_cntvoff",
        "virt/kvm/arm/arch_timer.c:get_timer_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503970056,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "virt/kvm/arm/hyp/vgic-v3-sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_activate_traps",
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_restore_state",
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_save_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490613416,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "arch/arm64/kvm/hyp/sysreg-sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/hyp/sysreg-sr.c:kvm_vcpu_put_sysregs",
        "arch/arm64/kvm/hyp/sysreg-sr.c:kvm_vcpu_load_sysregs",
        "arch/arm64/kvm/hyp/sysreg-sr.c:__sysreg32_restore_state",
        "arch/arm64/kvm/hyp/sysreg-sr.c:__sysreg32_save_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503975960,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "arch/arm64/kvm/hyp/debug-sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_host",
        "arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_guest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503977888,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "arch/arm64/kvm/hyp/switch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/hyp/switch.c:fixup_guest_exit",
        "arch/arm64/kvm/hyp/switch.c:__activate_traps",
        "arch/arm64/kvm/hyp/switch.c:activate_traps_vhe"
      ],
      "caller_func": [
        "arch/arm64/kvm/hyp/switch.c:hyp_panic"
      ]
    },
    {
      "addr": 18446603336503980224,
      "name": "has_vhe",
      "external": false,
      "loc": "arch/arm64/include/asm/virt.h:86",
      "file": "arch/arm64/kvm/hyp/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/hyp/tlb.c:__kvm_tlb_flush_vmid_ipa",
        "arch/arm64/kvm/hyp/tlb.c:__tlb_switch_to_guest"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490481616,
      "name": "has_vhe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336490613592,
      "name": "has_vhe",
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
bool has_vhe()
```
</details>
</li>
</ul>

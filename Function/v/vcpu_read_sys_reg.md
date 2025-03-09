# Function: <code>vcpu_read_sys_reg</code>

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
u64 vcpu_read_sys_reg(const struct kvm_vcpu * vcpu, int reg)
```

```json
{
  "name": "vcpu_read_sys_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490513532,
      "name": "vcpu_read_sys_reg",
      "external": true,
      "loc": "arch/arm64/kvm/sys_regs.c:68",
      "file": "arch/arm64/kvm/sys_regs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/sys_regs.c:access_ccsidr",
        "arch/arm64/kvm/sys_regs.c:access_vm_reg"
      ],
      "caller_func": [
        "virt/kvm/arm/arm.c:kvm_mpidr_to_vcpu",
        "virt/kvm/arm/mmu.c:kvm_toggle_cache",
        "virt/kvm/arm/mmu.c:kvm_set_way_flush",
        "virt/kvm/arm/mmio.c:io_mem_abort",
        "virt/kvm/arm/mmio.c:kvm_handle_mmio_return",
        "virt/kvm/arm/psci.c:kvm_psci_0_2_call",
        "arch/arm64/kvm/inject_fault.c:kvm_inject_undefined",
        "arch/arm64/kvm/inject_fault.c:inject_abt64",
        "arch/arm64/kvm/inject_fault.c:get_except64_pstate",
        "arch/arm64/kvm/debug.c:kvm_arm_clear_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/debug.c:kvm_arm_setup_debug",
        "arch/arm64/kvm/reset.c:kvm_reset_vcpu",
        "arch/arm64/kvm/sys_regs.c:trap_debug_regs",
        "arch/arm64/kvm/sys_regs.c:access_vm_reg",
        "virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi",
        "virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_read_v3r_typer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490520232,
      "name": "vcpu_read_sys_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
u64 vcpu_read_sys_reg(const struct kvm_vcpu * vcpu, int reg)
```
</details>
</li>
</ul>

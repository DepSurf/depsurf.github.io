# Function: <code>kvm_vcpu_kick</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void kvm_vcpu_kick(struct kvm_vcpu * vcpu)
```

```json
{
  "name": "kvm_vcpu_kick",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490395560,
      "name": "kvm_vcpu_kick",
      "external": true,
      "loc": "virt/kvm/kvm_main.c:2551",
      "file": "virt/kvm/kvm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init",
        "virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_set_mpstate",
        "virt/kvm/arm/psci.c:kvm_hvc_call_handler",
        "virt/kvm/arm/psci.c:kvm_psci_0_2_call",
        "virt/kvm/arm/vgic/vgic.c:vgic_kick_vcpus",
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate",
        "virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock",
        "virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock",
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_doorbell_handler",
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_doorbell_handler",
        "virt/kvm/arm/pmu.c:kvm_pmu_perf_overflow",
        "virt/kvm/arm/pmu.c:kvm_pmu_perf_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490395560,
      "name": "kvm_vcpu_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void kvm_vcpu_kick(struct kvm_vcpu * vcpu)
```
</details>
</li>
</ul>

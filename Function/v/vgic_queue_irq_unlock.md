# Function: <code>vgic_queue_irq_unlock</code>

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
bool vgic_queue_irq_unlock(struct kvm * kvm, struct vgic_irq * irq, long unsigned int flags)
```

```json
{
  "name": "vgic_queue_irq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490533424,
      "name": "vgic_queue_irq_unlock",
      "external": true,
      "loc": "virt/kvm/arm/vgic/vgic.c:334",
      "file": "virt/kvm/arm/vgic/vgic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_write_irq_line_level_info",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_group",
        "virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipends",
        "virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgir",
        "virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi",
        "virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_uaccess_write_pending",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_trigger_msi",
        "virt/kvm/arm/vgic/vgic-its.c:update_lpi_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490533424,
      "name": "vgic_queue_irq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
bool vgic_queue_irq_unlock(struct kvm * kvm, struct vgic_irq * irq, long unsigned int flags)
```
</details>
</li>
</ul>

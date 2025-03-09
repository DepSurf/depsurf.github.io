# Function: <code>vgic_get_mmio_region</code>

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
const struct vgic_register_region * vgic_get_mmio_region(struct kvm_vcpu * vcpu, struct vgic_io_device * iodev, gpa_t addr, int len)
```

```json
{
  "name": "vgic_get_mmio_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490559288,
      "name": "vgic_get_mmio_region",
      "external": true,
      "loc": "virt/kvm/arm/vgic/vgic-mmio.c:759",
      "file": "virt/kvm/arm/vgic/vgic-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic-mmio.c:dispatch_mmio_write",
        "virt/kvm/arm/vgic/vgic-mmio.c:dispatch_mmio_read",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_uaccess",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_uaccess",
        "virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_v2_has_attr_regs",
        "virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_has_attr_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490559288,
      "name": "vgic_get_mmio_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
const struct vgic_register_region * vgic_get_mmio_region(struct kvm_vcpu * vcpu, struct vgic_io_device * iodev, gpa_t addr, int len)
```
</details>
</li>
</ul>

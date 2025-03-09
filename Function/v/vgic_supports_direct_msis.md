# Function: <code>vgic_supports_direct_msis</code>

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
bool vgic_supports_direct_msis(struct kvm * kvm)
```

```json
{
  "name": "vgic_supports_direct_msis",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490567584,
      "name": "vgic_supports_direct_msis",
      "external": true,
      "loc": "virt/kvm/arm/vgic/vgic-mmio-v3.c:49",
      "file": "virt/kvm/arm/vgic/vgic-mmio-v3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate",
        "virt/kvm/arm/vgic/vgic-init.c:__kvm_vgic_destroy",
        "virt/kvm/arm/vgic/vgic-init.c:__kvm_vgic_destroy",
        "virt/kvm/arm/vgic/vgic-v4.c:kvm_vgic_v4_disable_doorbell",
        "virt/kvm/arm/vgic/vgic-v4.c:kvm_vgic_v4_enable_doorbell",
        "virt/kvm/arm/vgic/vgic-v4.c:kvm_vgic_v4_unset_forwarding",
        "virt/kvm/arm/vgic/vgic-v4.c:kvm_vgic_v4_set_forwarding",
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_flush_hwstate",
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_sync_hwstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490567584,
      "name": "vgic_supports_direct_msis",
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
bool vgic_supports_direct_msis(struct kvm * kvm)
```
</details>
</li>
</ul>

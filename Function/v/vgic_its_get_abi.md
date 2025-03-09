# Function: <code>vgic_its_get_abi</code>

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
const struct vgic_its_abi * vgic_its_get_abi(struct vgic_its * its)
```

```json
{
  "name": "vgic_its_get_abi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490587956,
      "name": "vgic_its_get_abi",
      "external": true,
      "loc": "virt/kvm/arm/vgic/vgic-its.c:185",
      "file": "virt/kvm/arm/vgic/vgic-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_commit_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:handle_l1_dte",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_dte",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_write_its_baser",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_mmio_read_its_typer"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490586368,
      "name": "vgic_its_get_abi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
const struct vgic_its_abi * vgic_its_get_abi(struct vgic_its * its)
```
</details>
</li>
</ul>

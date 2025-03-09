# Function: <code>hv_unmap_ioapic_interrupt</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_unmap_ioapic_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579054672,
      "name": "hv_unmap_ioapic_interrupt",
      "external": true,
      "loc": "arch/x86/hyperv/irqdomain.c:362",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054672,
      "name": "hv_unmap_ioapic_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_unmap_ioapic_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579075568,
      "name": "hv_unmap_ioapic_interrupt",
      "external": true,
      "loc": "arch/x86/hyperv/irqdomain.c:362",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075568,
      "name": "hv_unmap_ioapic_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_unmap_ioapic_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100896,
      "name": "hv_unmap_ioapic_interrupt",
      "external": true,
      "loc": "arch/x86/hyperv/irqdomain.c:341",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100896,
      "name": "hv_unmap_ioapic_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_unmap_ioapic_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579137504,
      "name": "hv_unmap_ioapic_interrupt",
      "external": true,
      "loc": "arch/x86/hyperv/irqdomain.c:341",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137504,
      "name": "hv_unmap_ioapic_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_unmap_ioapic_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138400,
      "name": "hv_unmap_ioapic_interrupt",
      "external": true,
      "loc": "arch/x86/hyperv/irqdomain.c:341",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138400,
      "name": "hv_unmap_ioapic_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_unmap_ioapic_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579165136,
      "name": "hv_unmap_ioapic_interrupt",
      "external": true,
      "loc": "arch/x86/hyperv/irqdomain.c:341",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579165136,
      "name": "hv_unmap_ioapic_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry * entry)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

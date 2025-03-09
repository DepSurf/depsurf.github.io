# Function: <code>map_ioapic_to_iommu</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct intel_iommu * map_ioapic_to_iommu(int apic)
```

```json
{
  "name": "map_ioapic_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586940163,
      "name": "map_ioapic_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:217",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select"
      ],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:parse_ioapics_under_ir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591481449,
      "name": "map_ioapic_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ioapic_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586821715,
      "name": "map_ioapic_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:218",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ioapic_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587381645,
      "name": "map_ioapic_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:218",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ioapic_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588691725,
      "name": "map_ioapic_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:218",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ioapic_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590165053,
      "name": "map_ioapic_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:216",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ioapic_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590479277,
      "name": "map_ioapic_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:212",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ioapic_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590829805,
      "name": "map_ioapic_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/irq_remapping.c:212",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct intel_iommu * map_ioapic_to_iommu(int apic)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct intel_iommu * map_ioapic_to_iommu(int apic)
```
</details>
</li>
</ul>

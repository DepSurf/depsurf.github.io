# Function: <code>x86_fwspec_is_ioapic</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec * fwspec)
```

```json
{
  "name": "x86_fwspec_is_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579303776,
      "name": "x86_fwspec_is_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:643",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303776,
      "name": "x86_fwspec_is_ioapic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071579309696,
      "name": "x86_fwspec_is_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec * fwspec)
```

```json
{
  "name": "x86_fwspec_is_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579306672,
      "name": "x86_fwspec_is_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:651",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306672,
      "name": "x86_fwspec_is_ioapic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071579312512,
      "name": "x86_fwspec_is_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec * fwspec)
```

```json
{
  "name": "x86_fwspec_is_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579354928,
      "name": "x86_fwspec_is_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:651",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354928,
      "name": "x86_fwspec_is_ioapic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071579361328,
      "name": "x86_fwspec_is_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec * fwspec)
```

```json
{
  "name": "x86_fwspec_is_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417627,
      "name": "x86_fwspec_is_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:651",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_select"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_select",
        "drivers/iommu/amd/iommu.c:irq_remapping_select",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417328,
      "name": "x86_fwspec_is_ioapic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579424320,
      "name": "x86_fwspec_is_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec * fwspec)
```

```json
{
  "name": "x86_fwspec_is_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579500747,
      "name": "x86_fwspec_is_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:647",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_select"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_select",
        "drivers/iommu/amd/iommu.c:irq_remapping_select",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500416,
      "name": "x86_fwspec_is_ioapic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579507968,
      "name": "x86_fwspec_is_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec * fwspec)
```

```json
{
  "name": "x86_fwspec_is_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579512907,
      "name": "x86_fwspec_is_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:647",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_select"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_select",
        "drivers/iommu/amd/iommu.c:irq_remapping_select",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512576,
      "name": "x86_fwspec_is_ioapic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579520224,
      "name": "x86_fwspec_is_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec * fwspec)
```

```json
{
  "name": "x86_fwspec_is_ioapic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579541382,
      "name": "x86_fwspec_is_ioapic",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:658",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_select"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_select",
        "drivers/iommu/amd/iommu.c:irq_remapping_select",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541056,
      "name": "x86_fwspec_is_ioapic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579548976,
      "name": "x86_fwspec_is_ioapic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec * fwspec)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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

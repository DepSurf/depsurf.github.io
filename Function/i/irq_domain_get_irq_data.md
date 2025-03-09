# Function: <code>irq_domain_get_irq_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579763504,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1006",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_find_mapping",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763504,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579788048,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1054",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786480,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579815168,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1080",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813600,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579812096,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1249",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811856,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579847054,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1249",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845872,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579880830,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1133",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879680,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579928110,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1133",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926960,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579966512,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1170",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965424,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580016287,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1172",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015200,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580068116,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1186",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064640,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050724,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1292",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046384,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050756,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1259",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:__msi_domain_free_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047248,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580183812,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1299",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:__msi_domain_free_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180144,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580332276,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1301",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irq_sim.c:irq_sim_domain_unmap",
        "kernel/irq/msi.c:__msi_domain_free_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328160,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580548900,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1361",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irq_sim.c:irq_sim_domain_unmap",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543840,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580622334,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1340",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irq_sim.c:irq_sim_domain_unmap",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580617296,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580687278,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1340",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irq_sim.c:irq_sim_domain_unmap",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682192,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491218172,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1172",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_free",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free",
        "drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_free",
        "drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_free",
        "drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_domain_free",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_domain_free",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_free",
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_free",
        "drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_free",
        "drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_free",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_free",
        "drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_free",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_free",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_free",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_free",
        "drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_free",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_irq_msi_domain_free",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491216784,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225233368,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1172",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_free",
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_free",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_free",
        "drivers/irqchip/irq-crossbar.c:crossbar_domain_free",
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_free",
        "drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_free",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225232160,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284122316,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1702",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284120208,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271755382,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1172",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271754252,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985023,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1172",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983936,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579922799,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1172",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921712,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579976559,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1172",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975472,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_data * irq_domain_get_irq_data(struct irq_domain * domain, unsigned int virq)
```

```json
{
  "name": "irq_domain_get_irq_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580023199,
      "name": "irq_domain_get_irq_data",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1172",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_pop_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_common",
        "kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip",
        "kernel/irq/irqdomain.c:irq_find_mapping"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:irq_force_complete_move",
        "arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs",
        "arch/x86/kernel/apic/vector.c:x86_vector_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022096,
      "name": "irq_domain_get_irq_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

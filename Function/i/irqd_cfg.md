# Function: <code>irqd_cfg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_cfg * irqd_cfg(struct irq_data * irq_data)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579192576,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:64",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:irq_cfg",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_activate",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192576,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct irq_cfg * irqd_cfg(struct irq_data * irq_data)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579195190,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:64",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_activate",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193152,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct irq_cfg * irqd_cfg(struct irq_data * irq_data)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579207350,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:64",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_activate",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204880,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct irq_cfg * irqd_cfg(struct irq_data * irq_data)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579203247,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:64",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_activate",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202736,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579220591,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:90",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_activate",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218672,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579235957,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:91",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_activate",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230768,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579259621,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:92",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_activate",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254464,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579273669,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_activate",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268480,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579276085,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_activate",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270848,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579298837,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd/iommu.c:irq_remapping_activate",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298528,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304293,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd/iommu.c:irq_remapping_activate",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304128,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579307189,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd/iommu.c:irq_remapping_activate",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307024,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579355445,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd/iommu.c:irq_remapping_activate",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_unmask_irq",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355280,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417877,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd/iommu.c:irq_remapping_activate",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_unmask_irq",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417712,
      "name": "irqd_cfg",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501045,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd/iommu.c:irq_remapping_activate",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_unmask_irq",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500848,
      "name": "irqd_cfg",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513205,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd/iommu.c:irq_remapping_activate",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_unmask_irq",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513008,
      "name": "irqd_cfg",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579541669,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:100",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd/iommu.c:irq_remapping_activate",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_unmask_irq",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541488,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579274789,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_activate",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269552,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579210133,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_activate",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204896,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579275989,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_activate",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270752,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```

```json
{
  "name": "irqd_cfg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579281877,
      "name": "irqd_cfg",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:89",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:irq_cfg"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/msi.c:msi_set_affinity",
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_activate",
        "arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_affinity",
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity",
        "drivers/iommu/amd_iommu.c:irq_remapping_activate",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity",
        "drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate",
        "drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276576,
      "name": "irqd_cfg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_data * irqd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct irq_data * irq_data</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct irq_cfg * irqd_cfg(struct irq_data * irqd)
```
</details>
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

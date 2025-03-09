# Function: <code>irq_domain_alloc_irqs_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768816,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1258",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768816,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579790016,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1314",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790016,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579817136,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1340",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817136,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810848,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1484",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810848,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579845008,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1654",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845008,
      "name": "irq_domain_alloc_irqs_parent",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579878928,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1538",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878928,
      "name": "irq_domain_alloc_irqs_parent",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579925984,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1538",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925984,
      "name": "irq_domain_alloc_irqs_parent",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579964176,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1575",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964176,
      "name": "irq_domain_alloc_irqs_parent",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013936,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1578",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013936,
      "name": "irq_domain_alloc_irqs_parent",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580068992,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1580",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068992,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050544,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1702",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050544,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050576,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1667",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050576,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580184160,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1712",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184160,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580332592,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1716",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580332592,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580548688,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1784",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548688,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580622112,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1765",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622112,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580687056,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1765",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687056,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491214912,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1578",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_gic_domain_alloc",
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_domain_alloc",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_domain_alloc",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_domain_alloc",
        "drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc",
        "drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_domain_alloc",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_ap_alloc",
        "drivers/irqchip/irq-sni-exiu.c:exiu_domain_alloc",
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc",
        "drivers/irqchip/qcom-pdc.c:qcom_pdc_alloc",
        "drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491214912,
      "name": "irq_domain_alloc_irqs_parent",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225230428,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1578",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-exynos/suspend.c:exynos_pmu_domain_alloc",
        "arch/arm/mach-imx/gpc.c:imx_gpc_domain_alloc",
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc",
        "drivers/irqchip/irq-tegra.c:tegra_ictlr_domain_alloc",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3-its.c:its_irq_gic_domain_alloc",
        "drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_alloc",
        "drivers/irqchip/irq-crossbar.c:crossbar_domain_alloc",
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_domain_alloc",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_domain_alloc",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_domain_alloc",
        "drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_domain_alloc",
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc",
        "drivers/irqchip/qcom-pdc.c:qcom_pdc_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/soc/tegra/pmc.c:tegra_pmc_irq_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225230428,
      "name": "irq_domain_alloc_irqs_parent",
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271752666,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1578",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271752666,
      "name": "irq_domain_alloc_irqs_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579982672,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1578",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982672,
      "name": "irq_domain_alloc_irqs_parent",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920448,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1578",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920448,
      "name": "irq_domain_alloc_irqs_parent",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974208,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1578",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974208,
      "name": "irq_domain_alloc_irqs_parent",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```

```json
{
  "name": "irq_domain_alloc_irqs_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020832,
      "name": "irq_domain_alloc_irqs_parent",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1578",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020832,
      "name": "irq_domain_alloc_irqs_parent",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain * domain, unsigned int irq_base, unsigned int nr_irqs, void * arg)
```
</details>
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

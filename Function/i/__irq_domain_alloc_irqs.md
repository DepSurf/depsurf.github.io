# Function: <code>__irq_domain_alloc_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579767088,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1172",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767088,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct cpumask * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579790064,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1227",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790064,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct cpumask * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579817184,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1253",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817184,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct cpumask * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815600,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1397",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815600,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 794
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct cpumask * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850992,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1398",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850992,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct cpumask * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884704,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1282",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884704,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931760,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1282",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931760,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970160,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1319",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970160,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019968,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1321",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019968,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070496,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1328",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070496,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052720,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1441",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/iommu/amd/init.c:iommu_setup_intcapxt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052720,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1408",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591247020,
      "name": "__irq_domain_alloc_irqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580052784,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1448",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592139964,
      "name": "__irq_domain_alloc_irqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580185232,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1069
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1451",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593910699,
      "name": "__irq_domain_alloc_irqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071580333280,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1050
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580551696,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1557",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580551696,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580625088,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1536",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625088,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580690096,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1536",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/iommu/amd/init.c:__iommu_setup_intcapxt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690096,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491222984,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1321",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491222984,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225237624,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1321",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225237624,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271759162,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1321",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271759162,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988704,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1321",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988704,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926480,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1321",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926480,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980240,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1321",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980240,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_domain_alloc_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026880,
      "name": "__irq_domain_alloc_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1321",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026880,
      "name": "__irq_domain_alloc_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask * affinity</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct cpumask * affinity</code> ➡️ <code>const struct irq_affinity_desc * affinity</code>
</li>
</ul>
</details>
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
int __irq_domain_alloc_irqs(struct irq_domain * domain, int irq_base, unsigned int nr_irqs, int node, void * arg, bool realloc, const struct irq_affinity_desc * affinity)
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

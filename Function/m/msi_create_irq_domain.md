# Function: <code>msi_create_irq_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774608,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:242",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774608,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797808,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:244",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797808,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579825088,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:264",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825088,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824592,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:264",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824592,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860160,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:267",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860160,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893936,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893936,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940992,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940992,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979632,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979632,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029280,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029280,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079936,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079936,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062288,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:285",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_create_irq_domain",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062288,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063024,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:285",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063024,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580196448,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:425",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196448,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580348672,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:679",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "drivers/pci/msi/irqdomain.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580348672,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580569664,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:850",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "drivers/pci/msi/irqdomain.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569664,
      "name": "msi_create_irq_domain",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580643792,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:847",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "drivers/pci/msi/irqdomain.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643792,
      "name": "msi_create_irq_domain",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709008,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:847",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "drivers/pci/msi/irqdomain.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain",
        "arch/x86/pci/xen.c:xen_create_pci_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709008,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491234104,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/fsl-mc-msi.c:fsl_mc_msi_create_irq_domain",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/soc/ti/ti_sci_inta_msi.c:ti_sci_inta_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491234104,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225247536,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225247536,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271765434,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271765434,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998016,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998016,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579936688,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936688,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579989552,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989552,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
```

```json
{
  "name": "msi_create_irq_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036288,
      "name": "msi_create_irq_domain",
      "external": true,
      "loc": "kernel/irq/msi.c:281",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "drivers/pci/msi.c:pci_msi_create_irq_domain",
        "drivers/base/platform-msi.c:platform_msi_create_irq_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036288,
      "name": "msi_create_irq_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct irq_domain * msi_create_irq_domain(struct fwnode_handle * fwnode, struct msi_domain_info * info, struct irq_domain * parent)
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

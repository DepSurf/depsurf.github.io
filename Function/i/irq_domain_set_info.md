# Function: <code>irq_domain_set_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766720,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1055",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/generic-chip.c:irq_map_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766720,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787856,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1104",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/generic-chip.c:irq_map_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787856,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814976,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814976,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813344,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1299",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813344,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846512,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1299",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846512,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880304,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1183",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880304,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927584,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1183",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927584,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965984,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1220",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965984,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015760,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1222",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015760,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067888,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1236",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067888,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050400,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1342",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050400,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050432,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1309",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050432,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580182336,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1349",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182336,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, const struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580330640,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1352",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330640,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, const struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546752,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1412",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546752,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, const struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621936,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1391",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621936,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, const struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686880,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1391",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686880,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491217520,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1222",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/irqchip/irq-gic.c:gic_irq_domain_map",
        "drivers/irqchip/irq-gic.c:gic_irq_domain_map",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_domain_alloc",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_ap_alloc",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_alloc",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_alloc",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_alloc",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_alloc",
        "drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_alloc",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_irq_msi_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491217520,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225232812,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1222",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/irqchip/irq-gic.c:gic_irq_domain_map",
        "drivers/irqchip/irq-gic.c:gic_irq_domain_map",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_alloc",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225232812,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284127072,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1722",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284127072,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271754826,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1222",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271754826,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984496,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1222",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984496,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579922272,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1222",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579922272,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579976032,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1222",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579976032,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void irq_domain_set_info(struct irq_domain * domain, unsigned int virq, irq_hw_number_t hwirq, struct irq_chip * chip, void * chip_data, irq_flow_handler_t handler, void * handler_data, const char * handler_name)
```

```json
{
  "name": "irq_domain_set_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022672,
      "name": "irq_domain_set_info",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1222",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/kernel/apic/msi.c:dmar_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022672,
      "name": "irq_domain_set_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct irq_chip * chip</code> ➡️ <code>const struct irq_chip * chip</code>
</li>
</ul>
</details>
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

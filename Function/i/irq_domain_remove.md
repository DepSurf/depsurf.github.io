# Function: <code>irq_domain_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763280,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:140",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping",
        "drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping",
        "drivers/base/regmap/regmap-irq.c:regmap_del_irq_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763280,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786304,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:138",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping",
        "drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping",
        "drivers/base/platform-msi.c:platform_msi_create_device_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786304,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813424,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:136",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping",
        "drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping",
        "drivers/base/platform-msi.c:platform_msi_create_device_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813424,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811696,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:238",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/base/platform-msi.c:platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811696,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579845712,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:239",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/base/platform-msi.c:platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845712,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879488,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:241",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/base/platform-msi.c:platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879488,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926768,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:241",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926768,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:241",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972261,
      "name": "irq_domain_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579965232,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014992,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:243",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014992,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069088,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:228",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069088,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051600,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:237",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/init.c:iommu_setup_intcapxt",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051600,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051632,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:238",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051632,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580184240,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:248",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184240,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580332704,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:248",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/irq/irq_sim.c:devm_irq_domain_create_sim",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580332704,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580549232,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:272",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/irq/irq_sim.c:devm_irq_domain_create_sim",
        "kernel/irq/msi.c:msi_remove_device_irq_domain",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549232,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580622640,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:279",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/irq/irq_sim.c:devm_irq_domain_create_sim",
        "kernel/irq/msi.c:msi_remove_device_irq_domain",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622640,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580687584,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:279",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "kernel/irq/irq_sim.c:devm_irq_domain_create_sim",
        "kernel/irq/msi.c:msi_remove_device_irq_domain",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_deinit",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/init.c:__iommu_setup_intcapxt",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_exit",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687584,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491216512,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:243",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_init",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_init",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_init",
        "drivers/irqchip/irq-gic-v4.c:its_free_vcpu_irqs",
        "drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs",
        "drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs",
        "drivers/irqchip/irq-partition-percpu.c:partition_create_desc",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_remove",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe",
        "drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_remove",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_remove",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_remove",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_remove",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_remove",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_unmap_msi",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_remove",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_remove",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_remove",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491216512,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225231840,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:243",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_init",
        "drivers/irqchip/irq-omap-intc.c:intc_of_init",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_init",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_init",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_init",
        "drivers/irqchip/irq-gic-v4.c:its_free_vcpu_irqs",
        "drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs",
        "drivers/irqchip/irq-partition-percpu.c:partition_create_desc",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_remove",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_remove",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_remove",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_remove",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_remove",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_teardown",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_unmap_msi",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_remove",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/soc/dove/pmu.c:dove_init_pmu_irq",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65217.c:tps65217_remove",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/memory/omap-gpmc.c:gpmc_remove",
        "drivers/memory/omap-gpmc.c:gpmc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225231840,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284119808,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:243",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284119808,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271753962,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:243",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271753962,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579983728,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:243",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983728,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579921504,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:243",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921504,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975264,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:243",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975264,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void irq_domain_remove(struct irq_domain * domain)
```

```json
{
  "name": "irq_domain_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580021888,
      "name": "irq_domain_remove",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:243",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/base/platform-msi.c:__platform_msi_create_device_domain",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021888,
      "name": "irq_domain_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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

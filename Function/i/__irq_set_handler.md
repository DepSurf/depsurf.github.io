# Function: <code>__irq_set_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756256,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:789",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/gpio/gpiolib.c:gpiochip_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756256,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579779136,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:847",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/gpio/gpiolib.c:gpiochip_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779136,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805072,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:856",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/gpio/gpiolib.c:gpiochip_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805072,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802800,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:961",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/gpio/gpiolib.c:gpiochip_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802800,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836928,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836928,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870800,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:982",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870800,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917840,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:982",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917840,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955888,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955888,
      "name": "__irq_set_handler",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005744,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005744,
      "name": "__irq_set_handler",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580055729,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055344,
      "name": "__irq_set_handler",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580038321,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1043",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037936,
      "name": "__irq_set_handler",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580039185,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1046",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038800,
      "name": "__irq_set_handler",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580171745,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1046",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580171360,
      "name": "__irq_set_handler",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580320489,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1044",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irq_sim.c:irq_sim_domain_unmap",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320064,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580534745,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1046",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irq_sim.c:irq_sim_domain_unmap",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534288,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580608089,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1061",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irq_sim.c:irq_sim_domain_unmap",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607632,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580672601,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1058",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irq_sim.c:irq_sim_domain_unmap",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672144,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491201944,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_free",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_domain_free",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491201944,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225221072,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/prm_common.c:omap_prcm_register_chain_handler",
        "arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_cleanup",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_free",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq",
        "drivers/soc/dove/pmu.c:dove_init_pmu_irq",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_irq_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225221072,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284105216,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/mpic.c:mpic_init",
        "arch/powerpc/platforms/pseries/setup.c:pseries_init_irq",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284105216,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271743582,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_free_resources",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271743582,
      "name": "__irq_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974480,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974480,
      "name": "__irq_set_handler",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579912288,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/irq_sim.c:irq_sim_init",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912288,
      "name": "__irq_set_handler",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966016,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966016,
      "name": "__irq_set_handler",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012544,
      "name": "__irq_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:1054",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "kernel/irq/msi.c:msi_domain_ops_init",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012544,
      "name": "__irq_set_handler",
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

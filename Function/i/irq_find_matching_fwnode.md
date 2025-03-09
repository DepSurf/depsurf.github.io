# Function: <code>irq_find_matching_fwnode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * irq_find_matching_fwnode(struct fwnode_handle * fwnode, enum irq_domain_bus_token bus_token)
```

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763072,
      "name": "irq_find_matching_fwnode",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:252",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "drivers/pci/probe.c:pci_set_bus_msi_domain",
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763072,
      "name": "irq_find_matching_fwnode",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583543685,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:235",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583714617,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:235",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583680005,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:242",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583853497,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:242",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583720655,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:277",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894313,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:277",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583978255,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:286",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157036,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:286",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584172111,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:286",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584374444,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:286",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584260021,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:288",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584358572,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:288",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584453211,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:290",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584553980,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:290",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584589867,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690556,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585268043,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:298",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585404426,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:298",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585425355,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:305",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585561338,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:305",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585305419,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:301",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585439754,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:301",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585762591,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:300",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585905594,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:300",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586947677,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:314",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587104650,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:314",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588106605,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:302",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588296570,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:302",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588381212,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:305",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588572698,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:305",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588677676,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:305",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588872506,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:305",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511081496,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-gic-v3-its-platform-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511082024,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-gic-v3-its-pci-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511082668,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496414272,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-mtk-sysirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-sysirq.c:irq_find_host",
        "drivers/irqchip/irq-mtk-sysirq.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496415892,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-mtk-cirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-cirq.c:irq_find_host",
        "drivers/irqchip/irq-mtk-cirq.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496417372,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-imx-gpcv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-gpcv2.c:irq_find_host",
        "drivers/irqchip/irq-imx-gpcv2.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496417616,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-mvebu-gicp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-gicp.c:irq_find_host",
        "drivers/irqchip/irq-mvebu-gicp.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496422268,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-mvebu-odmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-odmi.c:irq_find_host",
        "drivers/irqchip/irq-mvebu-odmi.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496432452,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-sni-exiu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-sni-exiu.c:irq_find_host",
        "drivers/irqchip/irq-sni-exiu.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496434148,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-meson-gpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-meson-gpio.c:irq_find_host",
        "drivers/irqchip/irq-meson-gpio.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496434856,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/qcom-pdc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/qcom-pdc.c:irq_find_host",
        "drivers/irqchip/qcom-pdc.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496439080,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-ti-sci-intr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ti-sci-intr.c:irq_find_host",
        "drivers/irqchip/irq-ti-sci-intr.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496440672,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-ti-sci-inta.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ti-sci-inta.c:irq_find_host",
        "drivers/irqchip/irq-ti-sci-inta.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496943716,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496946636,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/of.c:pci_host_bridge_of_msi_domain",
        "drivers/pci/of.c:irq_find_host",
        "drivers/pci/of.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497480180,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/acpi/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/irq.c:acpi_irq_create_hierarchy",
        "drivers/acpi/irq.c:acpi_unregister_gsi",
        "drivers/acpi/irq.c:acpi_gsi_to_irq"
      ],
      "caller_func": [
        "drivers/acpi/irq.c:acpi_irq_get"
      ]
    },
    {
      "addr": 18446603336511134108,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/acpi/arm64/iort.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/arm64/iort.c:iort_add_platform_device",
        "drivers/acpi/arm64/iort.c:acpi_configure_pmsi_domain",
        "drivers/acpi/arm64/iort.c:iort_get_device_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501646292,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/of/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/irq.c:of_msi_map_get_device_domain",
        "drivers/of/irq.c:irq_find_host",
        "drivers/of/irq.c:irq_find_host"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497480304,
      "name": "irq_find_matching_fwnode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224559988,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "arch/arm/mach-exynos/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/suspend.c:irq_find_host",
        "arch/arm/mach-exynos/suspend.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3224579404,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "arch/arm/mach-imx/gpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/gpc.c:irq_find_host",
        "arch/arm/mach-imx/gpc.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3224618736,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "arch/arm/mach-omap2/omap-wakeupgen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap-wakeupgen.c:irq_find_host",
        "arch/arm/mach-omap2/omap-wakeupgen.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229692936,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-alpine-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-alpine-msi.c:irq_find_host",
        "drivers/irqchip/irq-alpine-msi.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229696996,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-tegra.c:irq_find_host",
        "drivers/irqchip/irq-tegra.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3243561288,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-gic-v3-its-platform-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243561624,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-gic-v3-its-pci-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3229745752,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-renesas-rza1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-rza1.c:irq_find_host",
        "drivers/irqchip/irq-renesas-rza1.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229747664,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-crossbar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-crossbar.c:irq_find_host",
        "drivers/irqchip/irq-crossbar.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229748620,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-vf610-mscm-ir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-vf610-mscm-ir.c:irq_find_host",
        "drivers/irqchip/irq-vf610-mscm-ir.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229749320,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-mtk-sysirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-sysirq.c:irq_find_host",
        "drivers/irqchip/irq-mtk-sysirq.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229750736,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-mtk-cirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-cirq.c:irq_find_host",
        "drivers/irqchip/irq-mtk-cirq.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229751828,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-imx-gpcv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-gpcv2.c:irq_find_host",
        "drivers/irqchip/irq-imx-gpcv2.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229753652,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-uniphier-aidet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-uniphier-aidet.c:irq_find_host",
        "drivers/irqchip/irq-uniphier-aidet.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229755112,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/irq-meson-gpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-meson-gpio.c:irq_find_host",
        "drivers/irqchip/irq-meson-gpio.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229756016,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/irqchip/qcom-pdc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/qcom-pdc.c:irq_find_host",
        "drivers/irqchip/qcom-pdc.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230213168,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/of.c:pci_host_bridge_of_msi_domain",
        "drivers/pci/of.c:irq_find_host",
        "drivers/pci/of.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3230905908,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/soc/tegra/pmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/pmc.c:irq_find_host",
        "drivers/soc/tegra/pmc.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3234166824,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/of/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/irq.c:of_msi_map_get_device_domain",
        "drivers/of/irq.c:irq_find_host",
        "drivers/of/irq.c:irq_find_host"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291041748,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/of.c:pci_host_bridge_of_msi_domain",
        "drivers/pci/of.c:irq_find_host",
        "drivers/pci/of.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295084784,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/of/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/irq.c:of_msi_map_get_device_domain",
        "drivers/of/irq.c:irq_find_host",
        "drivers/of/irq.c:irq_find_host"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275619902,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/of.c:pci_host_bridge_of_msi_domain",
        "drivers/pci/of.c:irq_find_host",
        "drivers/pci/of.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278104944,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/of/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/irq.c:of_msi_map_get_device_domain",
        "drivers/of/irq.c:irq_find_host",
        "drivers/of/irq.c:irq_find_host"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584542027,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584641036,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584470187,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584570812,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584540027,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640716,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_matching_fwnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584647771,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_set_bus_msi_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584748412,
      "name": "irq_find_matching_fwnode",
      "external": false,
      "loc": "include/linux/irqdomain.h:297",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct irq_domain * irq_find_matching_fwnode(struct fwnode_handle * fwnode, enum irq_domain_bus_token bus_token)
```
</details>
</li>
</ul>

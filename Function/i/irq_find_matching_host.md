# Function: <code>irq_find_matching_host</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct irq_domain * irq_find_matching_host(struct device_node * node, enum irq_domain_bus_token bus_token)
```

```json
{
  "name": "irq_find_matching_host",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511082664,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
      "file": "drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496414264,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
      "file": "drivers/irqchip/irq-mtk-sysirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-sysirq.c:irq_find_host",
        "drivers/irqchip/irq-mtk-sysirq.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496415884,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
      "file": "drivers/irqchip/irq-mtk-cirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mtk-cirq.c:irq_find_host",
        "drivers/irqchip/irq-mtk-cirq.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496417364,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
      "file": "drivers/irqchip/irq-mvebu-gicp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-gicp.c:irq_find_host",
        "drivers/irqchip/irq-mvebu-gicp.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496422260,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
      "file": "drivers/irqchip/irq-mvebu-odmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-odmi.c:irq_find_host",
        "drivers/irqchip/irq-mvebu-odmi.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496432444,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
      "file": "drivers/irqchip/irq-sni-exiu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-sni-exiu.c:irq_find_host",
        "drivers/irqchip/irq-sni-exiu.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496434140,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
      "file": "drivers/irqchip/irq-ti-sci-inta.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ti-sci-inta.c:irq_find_host",
        "drivers/irqchip/irq-ti-sci-inta.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496946608,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "addr": 18446603336501646268,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "addr": 18446603336501642328,
      "name": "irq_find_matching_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
struct irq_domain * irq_find_matching_host(struct device_node * node, enum irq_domain_bus_token bus_token)
```

```json
{
  "name": "irq_find_matching_host",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224559988,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
      "file": "drivers/irqchip/irq-tegra.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-tegra.c:irq_find_host",
        "drivers/irqchip/irq-tegra.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3229745752,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
      "file": "drivers/irqchip/qcom-pdc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/qcom-pdc.c:irq_find_host",
        "drivers/irqchip/qcom-pdc.c:irq_find_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3230213168,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "addr": 3234162800,
      "name": "irq_find_matching_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
struct irq_domain * irq_find_matching_host(struct device_node * node, enum irq_domain_bus_token bus_token)
```

```json
{
  "name": "irq_find_matching_host",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291041736,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "addr": 13835058055295084772,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "addr": 13835058055295079520,
      "name": "irq_find_matching_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct irq_domain * irq_find_matching_host(struct device_node * node, enum irq_domain_bus_token bus_token)
```

```json
{
  "name": "irq_find_matching_host",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275619898,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "addr": 18446743936278104940,
      "name": "irq_find_matching_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:307",
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
      "addr": 18446743936278101528,
      "name": "irq_find_matching_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct irq_domain * irq_find_matching_host(struct device_node * node, enum irq_domain_bus_token bus_token)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct irq_domain * irq_find_matching_host(struct device_node * node, enum irq_domain_bus_token bus_token)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct irq_domain * irq_find_matching_host(struct device_node * node, enum irq_domain_bus_token bus_token)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct irq_domain * irq_find_matching_host(struct device_node * node, enum irq_domain_bus_token bus_token)
```
</details>
</li>
</ul>

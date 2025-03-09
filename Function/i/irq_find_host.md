# Function: <code>irq_find_host</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate ❓</summary>

```c
struct irq_domain * irq_find_host(struct device_node * node)
```

```json
{
  "name": "irq_find_host",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496414228,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-mtk-sysirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init"
      ]
    },
    {
      "addr": 18446603336496415848,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-mtk-cirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init"
      ]
    },
    {
      "addr": 18446603336496417328,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-imx-gpcv2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init"
      ]
    },
    {
      "addr": 18446603336496417576,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-mvebu-gicp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe"
      ]
    },
    {
      "addr": 18446603336496422224,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-mvebu-odmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init"
      ]
    },
    {
      "addr": 18446603336496432408,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-sni-exiu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-sni-exiu.c:exiu_dt_init"
      ]
    },
    {
      "addr": 18446603336496434104,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-meson-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init"
      ]
    },
    {
      "addr": 18446603336496434816,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/qcom-pdc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/qcom-pdc.c:qcom_pdc_init"
      ]
    },
    {
      "addr": 18446603336496439040,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-ti-sci-intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_probe"
      ]
    },
    {
      "addr": 18446603336496440632,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-ti-sci-inta.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe"
      ]
    },
    {
      "addr": 18446603336496943800,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_host_bridge_of_msi_domain"
      ]
    },
    {
      "addr": 18446603336501642440,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/irq.c:of_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496414228,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336496415848,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336496417328,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336496417576,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336496422224,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336496432408,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336496434104,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336496434816,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336496439040,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336496440632,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336496943800,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336501642440,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate ❓</summary>

```c
struct irq_domain * irq_find_host(struct device_node * node)
```

```json
{
  "name": "irq_find_host",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224559932,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "arch/arm/mach-exynos/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-exynos/suspend.c:exynos_pmu_irq_init"
      ]
    },
    {
      "addr": 3224579348,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "arch/arm/mach-imx/gpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/gpc.c:imx_gpc_init"
      ]
    },
    {
      "addr": 3224618680,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "arch/arm/mach-omap2/omap-wakeupgen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init"
      ]
    },
    {
      "addr": 3229692880,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-alpine-msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_init"
      ]
    },
    {
      "addr": 3229696940,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-tegra.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-tegra.c:tegra_ictlr_init"
      ]
    },
    {
      "addr": 3229745696,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-renesas-rza1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe"
      ]
    },
    {
      "addr": 3229747608,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-crossbar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-crossbar.c:irqcrossbar_init"
      ]
    },
    {
      "addr": 3229748564,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-vf610-mscm-ir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init"
      ]
    },
    {
      "addr": 3229749264,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-mtk-sysirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init"
      ]
    },
    {
      "addr": 3229750680,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-mtk-cirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init"
      ]
    },
    {
      "addr": 3229751772,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-imx-gpcv2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init"
      ]
    },
    {
      "addr": 3229753596,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-uniphier-aidet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe"
      ]
    },
    {
      "addr": 3229755056,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/irq-meson-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init"
      ]
    },
    {
      "addr": 3229755960,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/irqchip/qcom-pdc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/qcom-pdc.c:qcom_pdc_init"
      ]
    },
    {
      "addr": 3230210256,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_host_bridge_of_msi_domain"
      ]
    },
    {
      "addr": 3230905852,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/soc/tegra/pmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234162916,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/irq.c:of_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224559932,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3224579348,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3224618680,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3229692880,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 3229696940,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3229745696,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 3229747608,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3229748564,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3229749264,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3229750680,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3229751772,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3229753596,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 3229755056,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3229755960,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 3230210256,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 3230905852,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 3234162916,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate ❓</summary>

```c
struct irq_domain * irq_find_host(struct device_node * node)
```

```json
{
  "name": "irq_find_host",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291037984,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_host_bridge_of_msi_domain"
      ]
    },
    {
      "addr": 13835058055295079680,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/irq.c:of_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291037984,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 13835058055295079680,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate ❓</summary>

```c
struct irq_domain * irq_find_host(struct device_node * node)
```

```json
{
  "name": "irq_find_host",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275617680,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/pci/of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/of.c:pci_host_bridge_of_msi_domain"
      ]
    },
    {
      "addr": 18446743936278101604,
      "name": "irq_find_host",
      "external": false,
      "loc": "include/linux/irqdomain.h:313",
      "file": "drivers/of/irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/irq.c:of_irq_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278101604,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446743936275617680,
      "name": "irq_find_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
struct irq_domain * irq_find_host(struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct irq_domain * irq_find_host(struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct irq_domain * irq_find_host(struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct irq_domain * irq_find_host(struct device_node * node)
```
</details>
</li>
</ul>

# Function: <code>devm_ioremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583051024,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:25",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583051024,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:25",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345216,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:25",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583470592,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583492736,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:25",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583492736,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673952,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673952,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583891904,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:63",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583891904,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583976176,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:64",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976176,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584159145,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584158912,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584292889,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_resource"
      ],
      "caller_func": [
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292656,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584704912,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:64",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704912,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584818208,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:64",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584818208,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584863024,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863024,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585285840,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585285840,
      "name": "devm_ioremap",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586139536,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586139536,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587131088,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:69",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131088,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587393232,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:69",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587393232,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587727584,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:69",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587727584,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496177200,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_resource"
      ],
      "caller_func": [
        "drivers/irqchip/irq-mbigen.c:mbigen_device_probe",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/clk/hisilicon/clk.c:hisi_clk_alloc",
        "drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_probe",
        "drivers/clk/imx/clk-imx8qxp-lpcg.c:imx8qxp_lpcg_clk_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe",
        "drivers/mfd/altera-sysmgr.c:sysmgr_probe",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:read_dts_node",
        "drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_probe",
        "drivers/net/ethernet/freescale/fman/mac.c:mac_probe",
        "drivers/net/ethernet/freescale/fman/mac.c:set_fman_mac_params",
        "drivers/edac/altera_edac.c:altr_edac_device_probe",
        "drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc",
        "drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe",
        "drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe",
        "drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe",
        "drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496177008,
      "name": "devm_ioremap",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229498636,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_resource"
      ],
      "caller_func": [
        "drivers/bus/ti-sysc.c:sysc_map_and_check_registers",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe",
        "drivers/clk/hisilicon/clk.c:hisi_clk_alloc",
        "drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_probe",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_register",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/ti/edma.c:edma_xbar_event_map",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe",
        "drivers/ata/sata_highbank.c:ahci_highbank_probe",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create",
        "drivers/rtc/rtc-pl031.c:pl031_probe",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe",
        "drivers/mmc/host/cqhci.c:cqhci_pltfm_init",
        "drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229498344,
      "name": "devm_ioremap",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290451940,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/syscon.c:syscon_probe",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290451616,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275232220,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275231868,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584261625,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261392,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584196825,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584196592,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584245385,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_resource"
      ],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584245152,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void * devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size)
```

```json
{
  "name": "devm_ioremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584350217,
      "name": "devm_ioremap",
      "external": true,
      "loc": "lib/devres.c:68",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_resource"
      ],
      "caller_func": [
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/mfd/syscon.c:syscon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584349984,
      "name": "devm_ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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

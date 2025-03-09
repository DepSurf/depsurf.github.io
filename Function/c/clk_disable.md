# Function: <code>clk_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586081888,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:708",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_gather_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081888,
      "name": "clk_disable",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586491904,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:634",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586491904,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298624,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:634",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298624,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584374016,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:634",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584374016,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776320,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:697",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776320,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585004800,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:855",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585004800,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585110992,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:866",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585110992,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585316736,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:987",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316736,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585456992,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:995",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456992,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586184160,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:999",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_disable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586184160,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586303792,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:993",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-xilinx.c:xgpio_probe",
        "drivers/gpio/gpio-xilinx.c:xgpio_remove",
        "drivers/clk/clk-bulk.c:clk_bulk_disable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303792,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586174336,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:993",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_disable",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586174336,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586672656,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:993",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_disable",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672656,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587944768,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:1005",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_disable",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587944768,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589302768,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:1089",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:clk_disable_unprepare",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589302768,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589599280,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:1131",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:clk_disable_unprepare",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589599280,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589909056,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:1131",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:clk_disable_unprepare",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589909056,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497760920,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:995",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_suspend",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_remove",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe",
        "drivers/bus/imx-weim.c:weim_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/phy/phy-xgene.c:xgene_phy_hw_init",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_disable",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_resume",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_resume",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set",
        "drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get_direction",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_deinit_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_disable",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/clk/imx/clk.c:imx_clk_disable_uart",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert",
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert",
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_remove",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:ipu_remove",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_off",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on",
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_suspend",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_suspend",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_remove",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_remove",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_serial_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/imx.c:imx_uart_thaw",
        "drivers/tty/serial/imx.c:imx_uart_resume",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/msm_serial.c:msm_shutdown",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_suspend",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_suspend",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/ahci_imx.c:ahci_imx_host_stop",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_sata_disable",
        "drivers/ata/ahci_imx.c:imx_sata_disable",
        "drivers/ata/ahci_imx.c:imx_sata_disable",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_clks",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_clks",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_suspend",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_remove",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_remove",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_remove",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_remove",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_suspend",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_remove",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_runtime_suspend",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/watchdog/rtd119x_wdt.c:rtd119x_clk_disable_unprepare",
        "drivers/mmc/host/mmci.c:mmci_runtime_suspend",
        "drivers/mmc/host/mmci.c:mmci_remove",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable",
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable",
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable",
        "drivers/clocksource/timer-of.c:timer_of_cleanup",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_cmt.c:sh_cmt_stop",
        "drivers/clocksource/sh_cmt.c:sh_cmt_start",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/sh_tmu.c:__sh_tmu_disable",
        "drivers/clocksource/timer-rockchip.c:rk_timer_cleanup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_cleanup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-sp804.c:sp804_get_clock_rate",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497760920,
      "name": "clk_disable",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230575868,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:995",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init",
        "arch/arm/mach-omap2/display.c:omap_dss_reset",
        "arch/arm/mach-omap2/omap_hwmod.c:_disable_clocks",
        "arch/arm/mach-omap2/omap_hwmod.c:_disable_clocks",
        "arch/arm/mach-omap2/omap_hwmod.c:_disable_optional_clocks",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_suspend",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_remove",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe",
        "drivers/bus/imx-weim.c:weim_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_disable",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_resume",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set",
        "drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get_direction",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_remove",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-omap.c:omap_gpio_set_config",
        "drivers/gpio/gpio-omap.c:omap_clear_gpio_debounce",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_disable_clk",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_subsys_powerdown",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_deinit_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_remove",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_disable",
        "drivers/amba/bus.c:amba_put_disable_pclk",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/clk/imx/clk.c:imx_clk_disable_uart",
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx50_clocks_init",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_runtime_suspend",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_runtime_suspend",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_runtime_suspend",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_runtime_resume",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_runtime_resume",
        "drivers/clk/tegra/clk-dfll.c:tegra_dfll_runtime_resume",
        "drivers/clk/tegra/clk-emc.c:emc_set_timing",
        "drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5",
        "drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:ipu_remove",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend",
        "drivers/soc/imx/gpc.c:imx6_pm_domain_power_on",
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read",
        "drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read",
        "drivers/soc/tegra/pmc.c:tegra_powergate_enable_clocks",
        "drivers/soc/tegra/pmc.c:tegra_powergate_disable_clocks",
        "drivers/regulator/fixed.c:reg_clock_disable",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_serial_suspend",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/imx.c:imx_uart_thaw",
        "drivers/tty/serial/imx.c:imx_uart_resume",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/msm_serial.c:msm_shutdown",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_unmap",
        "drivers/iommu/exynos-iommu.c:sysmmu_tlb_invalidate_flpdcache",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable",
        "drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq",
        "drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_suspend",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_suspend",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_remove",
        "drivers/mfd/t7l66xb.c:t7l66xb_remove",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_suspend",
        "drivers/mfd/t7l66xb.c:t7l66xb_mmc_disable",
        "drivers/mfd/tc6387xb.c:tc6387xb_remove",
        "drivers/mfd/tc6387xb.c:tc6387xb_mmc_disable",
        "drivers/mfd/tc6387xb.c:tc6387xb_suspend",
        "drivers/mfd/tc6393xb.c:tc6393xb_suspend",
        "drivers/mfd/tc6393xb.c:tc6393xb_remove",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend",
        "drivers/mfd/omap-usb-tll.c:omap_tll_disable",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_clks",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_clks",
        "drivers/ata/ahci_imx.c:ahci_imx_host_stop",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_sata_disable",
        "drivers/ata/ahci_imx.c:imx_sata_disable",
        "drivers/ata/ahci_imx.c:imx_sata_disable",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/ti/cpts.c:cpts_unregister",
        "drivers/net/ethernet/ti/cpts.c:cpts_register",
        "drivers/usb/phy/phy-generic.c:nop_set_suspend",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_remove",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_resume",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_suspend",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_remove",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_probe",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_resume",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_suspend",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_remove",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_probe",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_remove",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_remove",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_remove",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_disable_clk",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_disable_clk",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_runtime_suspend",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_remove",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_resume_noirq",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_remove",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_work",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_set_emulation",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_get_temp",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_control",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_initialize",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_initialize",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_cpu_exit",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_target",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_target_intermediate",
        "drivers/mmc/host/mmci.c:mmci_runtime_suspend",
        "drivers/mmc/host/mmci.c:mmci_remove",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_resume",
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_suspend",
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_unregister",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable",
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable",
        "drivers/firmware/qcom_scm.c:qcom_scm_clk_disable",
        "drivers/clocksource/timer-of.c:timer_of_cleanup",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_cmt.c:sh_cmt_stop",
        "drivers/clocksource/sh_cmt.c:sh_cmt_start",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_disable",
        "drivers/clocksource/renesas-ostm.c:ostm_init",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/sh_tmu.c:__sh_tmu_disable",
        "drivers/clocksource/em_sti.c:em_sti_probe",
        "drivers/clocksource/em_sti.c:em_sti_stop",
        "drivers/clocksource/timer-rockchip.c:rk_timer_cleanup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_cleanup",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/timer-rockchip.c:rk_timer_probe",
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register",
        "drivers/clocksource/timer-sp804.c:sp804_get_clock_rate",
        "drivers/devfreq/exynos-bus.c:exynos_bus_probe",
        "drivers/devfreq/exynos-bus.c:exynos_bus_probe",
        "drivers/devfreq/exynos-bus.c:exynos_bus_passive_exit",
        "drivers/devfreq/exynos-bus.c:exynos_bus_exit",
        "drivers/devfreq/event/exynos-nocp.c:exynos_nocp_remove",
        "drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_remove",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "drivers/memory/mtk-smi.c:mtk_smi_clk_disable",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_remove",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_free",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_shutdown",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_resume",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_suspend",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port",
        "sound/soc/fsl/imx-audmux.c:audmux_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230575868,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "clk_disable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_disable",
      "external": false,
      "loc": "include/linux/clk.h:831",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_disable",
      "external": false,
      "loc": "include/linux/clk.h:831",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_disable",
      "external": false,
      "loc": "include/linux/clk.h:831",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_disable",
      "external": false,
      "loc": "include/linux/clk.h:831",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_disable",
      "external": false,
      "loc": "include/linux/clk.h:831",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_disable",
      "external": false,
      "loc": "include/linux/clk.h:831",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_disable",
      "external": false,
      "loc": "include/linux/clk.h:831",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_disable",
      "external": false,
      "loc": "include/linux/clk.h:831",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_disable",
      "external": false,
      "loc": "include/linux/clk.h:831",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clk_disable",
      "external": false,
      "loc": "include/linux/clk.h:831",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275893754,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:995",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_remove",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_remove",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_probe",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_apply",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_apply",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/spi/spi-sifive.c:sifive_spi_remove",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/clocksource/timer-of.c:timer_of_cleanup",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/timer-of.c:timer_of_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275893754,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585219520,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:995",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219520,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585171696,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:995",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585171696,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585407392,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:995",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585407392,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void clk_disable(struct clk * clk)
```

```json
{
  "name": "clk_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585514880,
      "name": "clk_disable",
      "external": true,
      "loc": "drivers/clk/clk.c:995",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_enable",
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_suspend",
        "drivers/base/power/clock_ops.c:__pm_clk_remove",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_read",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write",
        "drivers/misc/sram.c:sram_remove",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514880,
      "name": "clk_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void clk_disable(struct clk * clk)
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

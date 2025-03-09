# Function: <code>clk_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586076592,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:658",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586076592,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586489968,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:578",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586489968,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296688,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:578",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296688,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584375824,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:578",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375824,
      "name": "clk_prepare",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584782128,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:641",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782128,
      "name": "clk_prepare",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585013296,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:798",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585013296,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585120224,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:809",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585120224,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585328176,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:930",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328176,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585466208,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:938",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585466208,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586186064,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:942",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586186064,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586306192,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:936",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-xilinx.c:xgpio_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586306192,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586179360,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:936",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_resume",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586179360,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586681104,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:936",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_resume",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586681104,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587951632,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:948",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_resume",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587951632,
      "name": "clk_prepare",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589311968,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:1032",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:pm_clk_resume",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589311968,
      "name": "clk_prepare",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589609616,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:1074",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/base/power/clock_ops.c:pm_clk_resume",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589609616,
      "name": "clk_prepare",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589919648,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:1074",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/base/power/clock_ops.c:pm_clk_resume",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589919648,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497762056,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:938",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe",
        "drivers/bus/imx-weim.c:weim_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/phy/phy-xgene.c:xgene_phy_hw_init",
        "drivers/phy/phy-xgene.c:xgene_phy_hw_init",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_probe",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_register",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/amba/bus.c:amba_get_enable_pclk",
        "drivers/amba/bus.c:amba_pm_runtime_resume",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe",
        "drivers/clk/imx/clk.c:imx_register_uart_clocks",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/rockchip/clk.c:rockchip_clk_protect_critical",
        "drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk",
        "drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert",
        "drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert",
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert",
        "drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on",
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume",
        "drivers/tty/serial/8250/8250_of.c:of_serial_resume",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/imx.c:imx_uart_freeze",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_clks",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_resume",
        "drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_resume",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_runtime_resume",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe",
        "drivers/mmc/host/mmci.c:mmci_runtime_resume",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_resume",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/timer-sp804.c:sp804_get_clock_rate",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_resume",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497762056,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230580824,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:938",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp_twd.c:twd_local_timer_of_register",
        "arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init",
        "arch/arm/mach-mvebu/platsmp.c:armada_xp_sync_secondary_clk",
        "arch/arm/mach-imx/system.c:mxc_arch_reset_init",
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe",
        "arch/arm/mach-omap2/display.c:omap_dss_reset",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe",
        "drivers/bus/imx-weim.c:weim_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/ti-sysc.c:sysc_get_clocks",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off",
        "drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on",
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_get_soc_data",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-omap.c:omap_gpio_probe",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_probe",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pci-v3-semi.c:v3_pci_probe",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/amba/bus.c:amba_get_enable_pclk",
        "drivers/amba/bus.c:amba_pm_runtime_resume",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/clk/imx/clk.c:imx_register_uart_clocks",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_pericfg_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init",
        "drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe",
        "drivers/clk/rockchip/clk.c:rockchip_clk_protect_critical",
        "drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk",
        "drivers/clk/samsung/clk-exynos5420.c:exynos5x_clk_init",
        "drivers/clk/tegra/clk.c:tegra_init_from_table",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-dfll.c:dfll_init",
        "drivers/clk/tegra/clk-emc.c:emc_set_timing",
        "drivers/clk/ti/clk.c:omap2_clk_enable_init_clocks",
        "drivers/clk/ti/clk-814x.c:dm814x_adpll_enable_init_clocks",
        "drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume",
        "drivers/soc/imx/gpc.c:imx6_pm_domain_power_on",
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read",
        "drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read",
        "drivers/soc/tegra/pmc.c:tegra_powergate_enable_clocks",
        "drivers/regulator/fixed.c:reg_clock_enable",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume",
        "drivers/tty/serial/8250/8250_of.c:of_serial_resume",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/imx.c:imx_uart_freeze",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/meson_uart.c:meson_uart_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_console_setup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/msm_serial.c:msm_startup",
        "drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_resume",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_resume",
        "drivers/mfd/t7l66xb.c:t7l66xb_mmc_enable",
        "drivers/mfd/tc6387xb.c:tc6387xb_mmc_enable",
        "drivers/mfd/tc6387xb.c:tc6387xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_resume",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-host.c:usbhs_runtime_resume",
        "drivers/mfd/omap-usb-tll.c:usbtll_omap_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_clks",
        "drivers/ata/ahci_imx.c:imx_ahci_probe",
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/ata/ahci_imx.c:imx8_sata_enable",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/ti/cpts.c:cpts_create",
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/usb/phy/phy-generic.c:nop_set_suspend",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_resume",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_probe",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_resume",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_probe",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_cpu_init",
        "drivers/cpufreq/tegra20-cpufreq.c:tegra_target_intermediate",
        "drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe",
        "drivers/mmc/host/mmci.c:mmci_runtime_resume",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe",
        "drivers/clocksource/timer-of.c:timer_of_init",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_cmt.c:sh_cmt_clock_event_resume",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_setup",
        "drivers/clocksource/renesas-ostm.c:ostm_init",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/em_sti.c:em_sti_probe",
        "drivers/clocksource/timer-orion.c:orion_timer_init",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register",
        "drivers/clocksource/timer-sp804.c:sp804_get_clock_rate",
        "drivers/clocksource/timer-imx-tpm.c:tpm_timer_init",
        "drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe",
        "drivers/devfreq/exynos-bus.c:exynos_bus_probe",
        "drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe",
        "drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe",
        "drivers/memory/mvebu-devbus.c:mvebu_devbus_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_common_resume",
        "drivers/memory/mtk-smi.c:mtk_smi_common_probe",
        "drivers/memory/mtk-smi.c:mtk_smi_larb_resume",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write",
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_resume",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_suspend",
        "sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port",
        "sound/soc/fsl/imx-audmux.c:audmux_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230580824,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
  "name": "clk_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290853592,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/gpio/gpio-ftgpio010.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291146420,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/pci/controller/pci-ftpci100.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291841620,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/tty/serial/8250/8250_of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_of.c:of_serial_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291846744,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291854156,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292390780,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292431276,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292460376,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292551280,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293689588,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294335244,
      "name": "clk_prepare",
      "external": false,
      "loc": "include/linux/clk.h:236",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275901392,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:938",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/pwm/pwm-sifive.c:pwm_sifive_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/spi/spi-sifive.c:sifive_spi_probe",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/clocksource/timer-of.c:timer_of_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275901392,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585228736,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:938",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585228736,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585180912,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:938",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585180912,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585416608,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:938",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe",
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416608,
      "name": "clk_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int clk_prepare(struct clk * clk)
```

```json
{
  "name": "clk_prepare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585524304,
      "name": "clk_prepare",
      "external": true,
      "loc": "drivers/clk/clk.c:938",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-bulk.c:clk_bulk_prepare",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/base/power/clock_ops.c:__pm_clk_add",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk",
        "drivers/misc/sram.c:sram_probe",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/twl6040.c:twl6040_set_pll",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585524304,
      "name": "clk_prepare",
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
int clk_prepare(struct clk * clk)
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
